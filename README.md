# Between the Lines — Library Management Interface

A responsive library-management project built with HTML, CSS, and vanilla JavaScript. It starts with 50 sample books and supports public catalogue browsing without a sign-in.

## Open in VS Code

1. Open VS Code and choose **File → Open Folder…**.
2. Select this `Library-Management-Interface` folder.
3. Open `index.html` in a browser, or use VS Code's Live Server extension while editing.

## Portal requirements covered

- Add, edit, and delete book details
- Dynamic catalogue showing title, author, ISBN, category, and available copy quantity
- Search by title, author, or ISBN; filter by category and availability
- Dashboard counts for available and issued copies
- Issue and return actions that adjust available quantity and prevent issuing when none remain
- Issue form records borrower name, student/member ID, issue date, and due date
- Issued-books view shows borrower, book, issue date, due date, and overdue status
- Book, issue, and reading-list data persist in browser Local Storage

The issue form defaults to a 14-day loan period; the due date can be changed before confirming. Starter ISBNs are sample identifiers. Data is saved in the current browser and does not sync between visitors because this is a front-end-only project. To make it available online, publish the folder using a static web host.
