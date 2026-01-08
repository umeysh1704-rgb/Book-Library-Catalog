# LibTrack | Digital Library Manager

LibTrack is a modern, responsive web application designed for personal book collection management. It allows users to digitize their physical bookshelves, track reading progress, and maintain a persistent database of their library.

## 🚀 Key Features
- **Dynamic Book Inventory:** Add books with specific titles and authors to a visual grid.
- **Real-Time Search:** Instantly filter your collection using the search bar (matches by title or author).
- **Status Tracking:** Toggle books between 'Available' and 'Borrowed' to track your lending.
- **Live Statistics:** Dashboard showing total books, books currently out, and overall reading percentage.
- **Persistent Memory:** Integrated with Browser Local Storage so your data survives page refreshes.

## 🛠️ Technical Stack
- **HTML5:** Semantic structure for the sidebar and library grid.
- **CSS3:** Custom styling using Flexbox for a side-by-side layout and responsive grid cards.
- **JavaScript (ES6):** Core engine handling data logic, filtering, and storage.

## 📖 How It Works
1. **The Sidebar:** Acts as the command center for data entry and viewing stats.
2. **The Grid:** Uses a "Render" engine to build HTML cards dynamically based on the JavaScript Array.
3. **The Storage:** Every change triggers a `localStorage` update, ensuring no data loss.

## 💻 Development Highlights
The project focused on "Separation of Concerns," keeping the structure (HTML), design (CSS), and logic (JS) in independent files for better maintainability.
