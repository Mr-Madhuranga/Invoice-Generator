# Invoice Generator

This is a simple, client-side invoice generator built using HTML, Tailwind CSS for styling, and JavaScript for functionality. It allows users to create, edit, save, delete, and download invoices as PDF files directly in their browser.

## Features

* **Create New Invoices:** Easily generate new, blank invoices.
* **Rename Invoices:** Give your invoices descriptive names.
* **Add Items:** Include line items with descriptions, quantities, and prices.
* **Edit Items:** Modify the details of existing items.
* **Delete Items:** Remove unwanted items from an invoice.
* **Calculate Total:** Automatically calculates the total amount for each invoice.
* **Save Changes:** Persists invoice data in the browser's local storage, so your invoices are saved even if you close the page.
* **Delete Invoices:** Remove entire invoices from your saved list.
* **Download as PDF:** Generates and downloads a PDF version of your invoice, including the current date and time (Singapore time).

## Technologies Used

* **HTML:** For the basic structure and content of the web page.
* **Tailwind CSS:** A utility-first CSS framework for rapid styling.
* **JavaScript:** For handling user interactions, data manipulation, local storage, and PDF generation.
* **SweetAlert2:** A beautiful and responsive modal dialog library for user alerts and prompts.
* **jsPDF:** A client-side JavaScript library for generating PDF documents.

## How to Use

1.  **Open `index.html`:** Simply open the `index.html` file in your web browser.
2.  **Create a New Invoice:** Click the "Create New Invoice" button on the left sidebar. A new invoice will be added to the list.
3.  **Edit Invoice Details:** Click on an invoice in the list to start editing its details on the right side.
4.  **Rename Invoice:** Click the "Rename" button next to an invoice in the list to change its name.
5.  **Add Items:** In the invoice details, click the "Add Item" button to add a new line item. You'll be prompted to enter the item name, quantity, and price.
6.  **Edit Items:** Click the "Edit" button next to an item in the invoice details to modify its information.
7.  **Delete Items:** Click the "Delete" button next to an item to remove it from the invoice.
8.  **Save Changes:** Click the "Save Changes" button to store the updated invoice details in your browser's local storage.
9.  **Delete Invoice:** Click the "Delete" button next to an invoice in the list to permanently remove it.
10. **Download as PDF:** Click the "Download as PDF" button to generate and download a PDF file of the currently viewed invoice. The PDF will include the current date and time in Singapore time.

## Local Storage

Invoice data is stored in your browser's local storage. This means that the invoices you create will be available even after you close and reopen the page on the same browser. However, data is not shared between different browsers or devices. Clearing your browser's local storage will also delete the saved invoices.

## PDF Generation

The PDF generation is done entirely on the client-side using the jsPDF library. The downloaded PDF will contain the invoice name, a list of items with their quantities, prices, and totals, the overall total amount, and the **current date and time in Singapore time** when the PDF was generated.

