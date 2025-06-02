# 🔗 LinkVault - Enhanced Bookmark Manager

## Project Overview

LinkVault is a modern, client-side web application designed to be a personal, enhanced bookmark manager. It offers a robust and intuitive interface for organizing, storing, and managing your favorite web links. Unlike traditional browser bookmarking, LinkVault provides advanced features such as dynamic grid display, intelligent search, multiple sorting options, deduplication, **drag-and-drop reordering**, and flexible import/export capabilities.

Built with a focus on a seamless user experience and local data persistence, LinkVault ensures your valuable links are always at your fingertips, accessible directly from your browser.

## Features

* **Dynamic Bookmark Grid:** Links are displayed in an elegant, responsive grid layout that adapts to various screen sizes.
* **Add, Edit, Delete Bookmarks:** Full CRUD (Create, Read, Update, Delete) functionality for managing individual links.
* **Intelligent Data Fetching:** Automatically fetches website titles and favicons using Microlink API and Google Favicon service when a URL is added or edited.
* **Local Storage Persistence:** All bookmarks are saved directly in your browser's local storage, ensuring data persists across sessions.
* **Search Functionality:** Quickly find specific links using a real-time search bar.
* **Advanced Sorting:** Organize your links by name (A-Z, Z-A) or by date added (Oldest, Newest).
* **Drag-and-Drop Reordering:** Easily rearrange your bookmarks within the grid by dragging and dropping.
* **Deduplication:** Efficiently remove duplicate URLs from your collection with a single click.
* **Import/Export Options:**
    * **Import/Export JSON:** Backup and restore your entire bookmark collection in a structured JSON format.
    * **Import/Export HTML:** Seamlessly import bookmarks from standard HTML bookmark files (e.g., from browser exports) and export your LinkVault collection back into HTML format.
* **Dark Mode:** A toggle for a comfortable viewing experience in low-light environments.
* **Responsive Design:** Optimized for a consistent and accessible experience across desktop, tablet, and mobile devices.
* **User Notifications:** Provides subtle, non-intrusive feedback for various actions (e.g., bookmark added, deleted, imported).

## Technologies Used

* **HTML5:** For the core structure and content.
* **CSS3:** For styling, layout, and responsive design, including custom dark mode themes.
* **JavaScript (ES6+):** Powers all interactive features, data management, and API integrations.
* **Web Storage API (localStorage):** For client-side data persistence.
* **Microlink API:** Used for fetching rich metadata (title, description, logo/favicon) from URLs.
* **Google Favicon Service:** As a fallback for fetching favicons.
* **Sortable.js:** A powerful JavaScript library enabling the drag-and-drop reordering of list items.

## How to Use

1.  **Open LinkVault:** Simply open the `Link_Valut.html` file in any modern web browser.
2.  **Add a New Link:**
    * Click on any empty "Add Bookmark" box in the grid.
    * Enter the URL in the "Website URL" field.
    * Optionally, provide a "Custom Title." If left empty, LinkVault will attempt to fetch one automatically.
    * Click "Save Link."
3.  **Open a Link:** Click on any existing bookmark box. The link will open in a new tab.
4.  **Edit a Link:** `Ctrl + Click` (Windows/Linux) or `Cmd + Click` (macOS) on any existing bookmark box to open the edit modal.
5.  **Delete a Link:**
    * From the grid view: Hover over a link box and click the "×" icon that appears.
    * From the edit modal: Open the edit modal for a link and click the "Delete" button.
6.  **Search:** Type into the "🔍 Search links..." input field to filter bookmarks in real-time.
7.  **Sort:** Select an option from the "Sort by..." dropdown to rearrange your links.
8.  **Reorder (Drag & Drop):** Click and hold a bookmark box, then drag it to your desired position within the grid.
9.  **Deduplicate:** Click the "🗑️ Deduplicate" button to remove identical links.
10. **Import/Export:** Use the "⬇️ Export JSON", "⬆️ Import JSON", "📤 Export HTML", and "📁 Import HTML" buttons to manage your collection data.
11. **Toggle Dark Mode:** Click the "🌙" switch to enable or disable dark mode.

## Setup and Installation

This is a standalone HTML file and does not require any complex server-side setup or database configuration.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/NajmusAdib/LinkVault.git](https://github.com/NajmusAdib/LinkVault.git)
    ```
    (Replace `LinkVault` with your actual repository name if different)
2.  **Navigate to the Directory:**
    ```bash
    cd LinkVault
    ```
3.  **Open the File:** Double-click `Link_Valut.html` in your file explorer, or open it via your browser's file menu.

## Screenshots (Optional)

*(Consider adding a screenshot or GIF here to visually demonstrate the application's interface and key features, especially the drag-and-drop functionality, in both light and dark mode.)*

## Contributing

Contributions are highly appreciated! If you have suggestions for new features, improvements, or bug fixes, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'feat: Add new feature X'`).
5.  Push to the branch (`git push origin feature/your-feature-name`).
6.  Open a Pull Request.

## License

This project is open-sourced under the [MIT License](LICENSE).

---

## Author

**Najmus Adib**
* [GitHub Profile](https://github.com/NajmusAdib)

---
