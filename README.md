# Organization
- [ ] Centralized Infrastructure Services
    - [ ] source repository
    - [ ] build automation
    - [ ] artifact repository
    - [ ] quality automation
    - [ ] quality dashboard
    - [ ] deployment automation
    - [ ] deployment dashboard
    - [ ] log repository
    - [ ] monitoring dashboard
    - [ ] alert dashboard
    - [ ] bug and feature tracking
- [ ] Defined Policies
- [ ] Defined Supported Languages

# Team Norms
- [ ] Are defined
    - [ ] Who merges a pull request?
    - [ ] Who administers source repository?
    - [ ] Where is team chat?
    - [ ] Desired and expected behaviors
- [ ] Ceremonies
    - [ ] Cadence defined
    - [ ] Bug review
    - [ ] Work planning
    - [ ] Feature demonstration
    - [ ] Release reviews
- [ ] Work Cycle includes
    - [ ] new features
    - [ ] cleanup
    - [ ] refactor
    - [ ] rewrite
    
# Source Code
- [ ] Source code in source repository
- [ ] Defined branch strategy
    - [ ] master (active) branch 
    - [ ] Feature branches
    - [ ] Release branches
- [ ] Changesets
    - [ ] Push disallowed on master
    - [ ] Pull requests from feature branches to master
    - [ ] Accepted pull request merge squashed to master
    - [ ] Branch from master to create release
    - [ ] Pull request cherry-pick from master to patch release
    - [ ] Tags are immutable
- [ ] Pull Request Guidelines
    - [ ] changes are small and atomic
    - [ ] anyone in organization can submit
    - [ ] must be approved by team member
- [ ] Code Review
     - [ ] happen
     - [ ] occur before code is pushed to master
     - [ ] enforced at pull request
- [ ] Source repository policies
    - [ ] readable by appropriate organization
    - [ ] write limited to team
    - [ ] administration by team member
    - [ ] policy enforcement
- [ ] Source Dependencies
    - [ ] are known
    - [ ] have specified version
    - [ ] originate from trusted source
    - [ ] hosted by durable artifact repository
    - [ ] are immutable
    - [ ] scanned for known vulnerabilities
    - [ ] scanned for license compliance
- [ ] Code Syntax & Style Guides
    - [ ] defined
    - [ ] automated
    - [ ] enforced
    - [ ] available in IDE
    - [ ] part of build
- [ ] Unit tests
    - [ ] in code
    - [ ] in source control
    - [ ] available in IDE
    - [ ] part of build
- [ ] Static Code Analysis
    - [ ] available in IDE
    - [ ] part of build
    - [ ] detects bugs
    - [ ] detects security vulnerabilities
    - [ ] assesses maintainability
    
# Build
- [ ] Push to source repository triggers build
- [ ] inputs
    - [ ] source pulled from source repository
    - [ ] dependencies pulled from artifact repository
    - [ ] tools pulled from trusted artifact repository
- [ ] process
    - [ ] scripted
    - [ ] deterministic and repeatable
    - [ ] in source control
    - [ ] triggered by source control push
- [ ] outputs
    - [ ] durable
    - [ ] in artifact repository

# Quality
- [ ] triggered by build completion
- [ ] Feature tests
    - [ ] defined
    - [ ] scripted
    - [ ] in source control
    - [ ] automated
- [ ] Results dashboard

# Service Documentation
- [ ] Design Doc
- [ ] API Doc
- [ ] Security Review
- [ ] Operation Service Doc
- [ ] Deployment Doc
- [ ] Alerts Runbook
- [ ] Central Location for all documents

# Deployment
- [ ] Staged
    - [ ] Product feature tested in stage
- [ ] Production
    - [ ] deployments do not require outage
    - [ ] Product feature tested after/during deployments
- [ ] Frequent
    - [ ] Quarterly or more often
    - [ ] Monthly or more often
    - [ ] Fortnightly or more often
    - [ ] Weekly or more often
    - [ ] Continuous
- [ ] process
    - [ ] documented
    - [ ] scripted
    - [ ] in source control
    - [ ] automatically triggered

# Production Operations
- [ ] Logging
- [ ] Monitoring
- [ ] Alerts
- [ ] Post mortems
- [ ] Chaos games

# Bug Tracking
- [ ] Bug Dashboard
- [ ] Triage

<p align="center">
  <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png"/></a>
  <br />
  This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
</p>