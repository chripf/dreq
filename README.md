dreq
====

A <b>D</b>rupal-based <b>Req</b>uirements enginiering system.


Basic Workflow
---

1. Define and plan story.
2. Implement story and define testcases.
3. Repeat testcases for each release. Update them if required, add new ones or automate more.
4. Hopefully step one has been running in parallel, so go to step 2.

Basic elements
---

    Story
    |- Title
    |- Descriptions
    |- Acceptance criteria
    |- Metadata
      |- Release
      |- Sprint
      |- Stakeholders
    |- Testcases
    
    Testcase
    |- Title
    |- Prerequisites
    |- Description
    |- Expected result
    |- Execution Info
      |- For Release
      |- Tester
      |- Result
    
    Stakeholders
    |- Name
    |- Additional Info
