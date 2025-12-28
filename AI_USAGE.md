# AI Usage

I used ChatGPT as a support tool while working on this assignment.

I used it to:
- confirm my understanding of the assignment requirements and my overall approach
- double-check my interpretation of business rules and edge cases, including clarifying some assumptions
- compare my implementation step by step with suggested approaches

All code was written, tested, and committed by me.

## Assumptions

I followed the existing style of the methods in LibraryService to write new error reason strings.
I interpreted reserving an available book would result in an immediate loan (for eligible member).
I applied the same limit rules to both borrowing and reserving.  
For handling returns, I interpreted “keeping the queue consistent” as a need to remove skipped reservers 
(for example, missing or ineligible members) to prevent the reservation queue from becoming blocked.  
I also kept the existing generic failure response for return operations.  
I have only refactored the method explicitly requested by the assignment, 
did not change other methods even where some repetitive patterns were present.