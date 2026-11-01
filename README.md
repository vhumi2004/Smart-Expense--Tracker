# Smart-Expense--Tracker
Smart Expense Tracker is a responsive web app built with HTML, CSS, JavaScript and Chart.js. Users add income and expenses, view total income, expenses and balance, manage transaction history, and see a category-wise expense chart. Data is saved in the browser with localStorage, so no backend or login is needed.
Users add transactions through a simple form, choosing whether each entry is income or an expense and assigning it a category. The app instantly calculates total income, total expenses, and the available balance, and shows them on a dashboard. Every transaction appears in a history list, and individual entries can be deleted when needed.

To make spending easier to understand, the app displays an expense breakdown chart by category using Chart.js. This lets users see at a glance where most of their money goes.

All transaction data is stored in the browser using localStorage, so records stay saved even after the page is refreshed or closed, with no backend or login required. The layout adapts to desktop, tablet, and mobile screens.

Through this project, I practiced DOM manipulation, event handling, array and data processing in JavaScript, working with the Web Storage API, and integrating a third-party library.

Tech stack: HTML5, CSS3, JavaScript (ES6+), Chart.js, localStorage

Note: Chart.js loads from the internet, so a connection is needed for the chart to display.
