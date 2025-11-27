# miniBookManagement
Objective

Build a simple DOM-based Book Management Application using HTML, CSS, and JavaScript that allows adding, viewing, sorting, filtering, and deleting books.

- Add a minimal styling for all the pages, focus more on functionality

Structure
Your app must have two pages:

1️⃣ index.html → Home Page 2️⃣ admin.html → Book Management Page

🔹 Common Requirement
- Both pages should have correct navigation through buttons or links.
- When button/link is clicked → the respective page should open.

Page Details

🏠 1. index.html (Home Page)
This page should contain:

- A heading → "Welcome to Book Management App"
- A button → "Go to Admin Page"

📌 On clicking the button: → Redirect to admin.html

🧑‍💼 2. admin.html (Book Management Page)
This page will handle all book operations:

⭐ Add Book Form

Fields:
- Title (text)
- Author (text)
- Category (select dropdown):
    - Fiction
    - Comedy
    - Technical

📌 On clicking Add Book:

- Create a book object in JS
- Add it to an array
- Display it immediately as a card below the form, render all the cards in the grid layout which is placed in the center of the screen
- Attach good box shadows, style good minimal styles for card

🔄 Sort Option
- A button: Sort by Title A → Z & Sort by Title Z → A
- On click → Sort the books alphabetically by title and re-render UI

🎯 Filter Option
- A dropdown to filter by Category
    - All
    - Fiction
    - Comedy
    - Technical
- On change → show only the selected category books

🗂️ Books Display Section
Display books in a grid layout Each card must show:

- Book Image (same for all)
- Title
- Autho
- Category
- Delete Button → removes that book from array + UI

Book Object Format
Each book should follow this structure:

{
  title: "Book Title",
  author: "Author Name",
  category: "Fiction",
  imageUrl: "https://m.media-amazon.com/images/I/71ZB18P3inL._SY522_.jpg"
}

📌 Use this image for all books
https://m.media-amazon.com/images/I/71ZB18P3inL._SY522_.jpg

Special Instructions
- Ensure UI updates correctly on:
    - Add
    - Sort
    - Filter
    - Delete
- Good and clean DOM code will be given preference
- Focus on functionality over styling

