project:
  name: Expense Tracker
  live_url: https://vamohammedilyas.github.io/Expence_tracker/
  description: >
    A simple, interactive web application to track income and expenses,
    built with HTML, CSS, and JavaScript. Transactions are stored in the
    browser via localStorage so data persists across sessions.
  version: 1.0.0

author:
  name: Mohammed Ilyas
  email: mohammedilyasva2004@gmail.com
 

technologies:
  - html
  - css
  - javascript


features:
  - Add income or expense transactions
  - View transaction history
  - Delete transactions
  - Show balance, total income, and total expense
  - Data persistence using localStorage
  - Responsive UI

project_structure:
  - index.html       # Main HTML file with app structure
  - style.css        # CSS styles and layout
  - script.js        # JavaScript logic and interaction

setup:
  prerequisites:
    - Modern web browser (Chrome, Firefox, Safari, Edge)
  steps:
    - Clone or download the repo
    - Navigate into project directory
    - Open index.html in browser
    - Use the app via live link or locally

usage:
  - Enter a description (text) for your transaction
  - Enter an amount (positive = income, negative = expense)
  - Click “Add transaction”
  - The UI updates balance, income, expense automatically
  - Click the delete (❌) button to remove a transaction
  - Refreshing the page keeps data (thanks to localStorage)

future_improvements:
  - Add categories (Food, Travel, Utilities, etc.)
  - Graphs and charts (using Chart.js or similar)
  - Monthly / weekly filtering
  - Export data (CSV, PDF)
  - Theme toggle (Dark / Light mode)
  - Link to backend or cloud storage for multi-device sync

