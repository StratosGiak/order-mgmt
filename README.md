## Customer Order Management app

This repo exists to showcase the cross-platform customer order management app I developed for a small business looking to digitize its operations.

The app is written using the Flutter framework, and it is available on desktop (native and browser) and mobile (iOS and Android).


Customer orders are logged into the app via a form, and are instantly made available to all other users of the app, enabling an efficient workflow for managing data.

Access to the underlying API is managed via a username/password login system.

Users can add, modify, or delete orders, with fields especially tailored for easy and intuitive access, eg. drop-down lists for constrained fields, autocomplete suggestions for common items, date pickers etc. Attaching multiple supplementary photos to each customer order is also supported.
Users can also view all existing orders arranged in a table, with columns containing the most relevant data. The table fully supports filtering for search terms, as well as ordering rows according to the values in a chosen column.
Finally, convenient features such as sending SMS messages to customers and automatically generating invoices in PDF format are present.


The backend constists of a Node.js server written entirely in TypeScript, using the Express.js framework to expose REST API endpoints to the app. The underlying data is stored in a SQL database following good practices ensuring data integrity. The server application is containerized using Docker, and is deployed to a cloud VPS.

_Disclaimer: All data present in the demo is randomly generated, with no reference to any real-world data_

### Demo

https://github.com/user-attachments/assets/367af67f-0b81-45da-8f7b-2d03ee626c42

https://github.com/user-attachments/assets/b4de97df-9640-4867-99f0-fe97e9f93650

