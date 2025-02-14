# Unhandled Database Query Error in Express.js Route Handler

This repository demonstrates a common error in Express.js applications:  failure to handle potential errors during database queries within route handlers.

The `bug.js` file shows the problematic code.  The route handler fetches user data; however, it lacks error handling for the database query. If the query fails (e.g., due to a database connection error or incorrect query), the application will crash.

The `bugSolution.js` file provides the corrected code, including robust error handling to gracefully manage query failures and respond appropriately to the client.