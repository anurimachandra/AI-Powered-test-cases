# AI-Powered-test-cases
Generating Manual Test Cases using AI Tool
# Generating Manual Test Cases using AI Tool

**Objective:** To generate manual test cases for the below user story using an AI tool.

**User Story:**
As an administrator,
I want to be able to add new users to the system
so that I can grant access to authorized personnel.

Acceptance Criteria:

    Verify that a new user can be created with a unique username and password.
    Verify that the administrator can assign different roles to new users.
    Verify that an email notification is sent to the new user upon account creation.

**Steps to Generate Test Cases using AI Tool:**

1.  Open the AI tool: [https://gemini.google.com/]
2.  Enter the following prompt: `Write functional test cases for the below user story in .csv format:`
3.  Paste the User Story and Acceptance Criteria into the prompt.
4.  Click "Enter" (or the equivalent button in the AI tool).

**Example of AI Generated Test Cases:**


The AI will generate test cases in a format suitable for saving as a `.csv` file.

**Validating Test Case Coverage in Excel:**

The generated test cases should now be saved as a `.csv` file, which can then be opened in Microsoft Excel for validation to ensure complete test case coverage.

**Adding Additional Columns:**

**NOTE:** If an additional column is required in the test case template, submit a new prompt specifying the column to be added (e.g., `"Add Test data field in the above template"`).

**Adding "Test Data" Column:**

To add a "Test Data" column and populate it with relevant data, use a prompt similar to:

`Please add a "Test Data" column to the test template and populate it with relevant test data for each test case.`

**Implementing Shift Left Testing with "Test Layer" Column:**

To further enhance our testing strategy by implementing shift-left principles, we can also add a "Test Layer" column. This will allow us to clearly identify which tests should be executed at each level of the test pyramid (Unit/Integration/E2E/Performance).

Prompt used: `Please add a "Test Layer" column to each row of the test case data, including the relevant layer name, so all details will be available in one CSV file.`

**Reviewing Generated Test Cases:**

The next step is to review the AI-generated test cases to confirm that they adequately cover all intended functionalities and scenarios.
