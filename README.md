# Daily-Expenses-Sharing-Application
Design and implement a backend for a daily-expenses sharing application. This 
application will allow users to add expenses and split them based on three 
different methods: exact amounts, percentages, and equal splits. The 
application should manage user details, validate inputs, and generate 
downloadable balance sheets.

Requirements:
User Management:
✓ Each user should have an email, name, and mobile number.
Expense Management:
✓ Users can add expenses.
 Expenses can be split using three methods:
1. Equal: Split equally among all participants.
2. Exact: Specify the exact amount each participant owes.
3. Percentage: Specify the percentage each participant owes. (Ensure 
percentages add up to 100%).
Expense Calculation Examples:
1. Equal:
Scenario: You go out with 3 friends. The total bill is 3000. Each friend owes 
1000.
2. Exact:
Scenario: You go shopping with 2 friends and pay 4299. Friend 1 owes 799, 
Friend 2 owes 2000, and you owe 1500.
3. Percentage:
Scenario: You go to a party with 2 friends and one of your cousins. You owe 
50%, Friend 1 owes 25%, and Friend 2 owes 25%.
Balance Sheet:
✓ Show individual expenses.
✓ Show overall expenses for all users.
✓ Provide a feature to download the balance sheet.
 
 Deliverables:
Backend Service:
Design the backend service to handle user and expense management.
API Endpoints:
User Endpoints:
✓ Create user.
✓ Retrieve user details.
 Expense Endpoints:
✓ Add expense.
✓ Retrieve individual user expenses.
✓ Retrieve overall expenses.
✓ Download balance sheet.
Data Validation:
✓ Validate user inputs.
✓ Ensure percentages in the percentage split method add up to 100%.
Documentation:
✓ Include setup and installation instructions.
✓ Write clear and concise code comments.
Evaluation Criteria:
1. Correctness: Functionality meets the requirements.
2. Code Quality: Code is clean, readable, and maintainable.
3. Documentation: Clear and comprehensive documentation.
4. Innovation: Creative and efficient solutions.
