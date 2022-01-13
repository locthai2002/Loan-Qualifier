# Loan-Qualifier
 Loan qualifier app along with all loan related tools

## User Story
As a user, I need the ability to save the qualifying loans to a CSV file so that I can share the results as a spreadsheet.

### Acceptance Criteria
Given that I’m using the loan qualifier CLI, when I run the qualifier, then the tool should prompt the user to save the results as a CSV file.

Given that no qualifying loans exist, when prompting a user to save a file, then the program should notify the user and exit.

Given that I have a list of qualifying loans, when I’m prompted to save the results, then I should be able to opt out of saving the file.

Given that I have a list of qualifying loans, when I choose to save the loans, the tool should prompt for a file path to save the file.

Given that I’m using the loan qualifier CLI, when I choose to save the loans, then the tool should save the results as a CSV file.