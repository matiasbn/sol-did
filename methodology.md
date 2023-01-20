# Methodology

## Audit

The audit consists in 3 different phases that coincide:

QA from team
Code Overhaul
Smellies discussion

- QA from team
- Code overhaul
  - The Code overhaul phase is where we sit down to understand what the code is doing, contrasting it with the Star Atlas team's expectations. In this phase, we build frames in Miro to separate the program functionality, analyzing every different entrypoint:
    - For every program entrypoint
      - Information discovery of program
      - Code overhaul file creation
      - Miro frame creation:
        - Who can call this function
        - What is the name of the entrypoint
        - What are the accounts necessary to trigger this function
        - What are the validations that need to happen (Accounts verification and Prerequisites)
        - What state changes are occurring after the transaction that triggered this function was successfully validated and broadcasted
- Smellies discussion
  - Internal discussion
  - Discussion with client

After finishing this phase, we are ready to redact the findings to discuss them

## Report

In this phase, we redact the findings, review them internally to generate the report, and send them for PR

- Findings generation:
  - After discussing our smellies, the auditors build the artifacts for the findings. In an internal review process, auditors of the same project review each other findings to discuss content and format. After being reviewed, the report is generated.
- Internal findings discussion:
- Sent to PR
- PR review discussion finished
