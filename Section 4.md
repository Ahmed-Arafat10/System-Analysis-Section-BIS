## Section 4 : Practicing On DFD

### By TA. Ahmed Arafat

- Website to draw DFD: https://creately.com/lp/data-flow-diagram-software-online/

## Case 1: University Admission System

- Student can `perform intake procedure` after sending his data to the system resulting in storing his data
- Then the system will send `admission approval or rejection`
- after student application approval, admin can request for student information in order to `maintain student information`
  which results in updating student information from the database
- Also, Admin can request for a report so that he can view students' reports

### Context Diagram


### Level 0



- `perform intake procedure` process can be broken to include the following
    - first it receives student data then stores it
    - it sends admission application to verify it, leading to updating admission application in the database
    - the last functionality is to review the admission application which will lead to updating its status in the
      database to `reviewed` status, also sending approval or rejection msg to the student

### Level 1
