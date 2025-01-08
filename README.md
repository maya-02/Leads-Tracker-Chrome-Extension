# Chrome Extension: Lead Tracker

## Overview
The **Lead Tracker** Chrome extension helps you save and organize your leads (URLs). It allows you to save the current browser tab, input custom URLs, and view them in a list. All leads are stored locally using `localStorage`, ensuring your data is preserved even after refreshing the browser.

---

## Features
- **Save Current Tab**: Click the "Save Tab" button to store the URL of the currently active tab.
- **Add Custom Leads**: Enter any URL in the input field and save it to your list.
- **View Leads**: All saved URLs are displayed as clickable links in an organized list.
- **Delete Leads**: Double-click the "Delete All" button to clear all saved leads.

---

## How to Use
1. **Save a Tab**:
   - Click the "Save Tab" button to save the URL of your currently active browser tab.
2. **Add a Custom URL**:
   - Enter a URL into the input field and click the "Save Input" button to add it to your list.
3. **View Leads**:
   - Your saved leads will appear in a list, with each URL clickable and opening in a new tab.
4. **Clear All Leads**:
   - Double-click the "Delete All" button to remove all saved leads.

---

## How It Works
- **Saving Leads**:
  - URLs are stored in the `myLeads` array and saved in `localStorage`.
- **Rendering Leads**:
  - The `render` function dynamically updates the list of leads in the DOM.
- **Tab Capture**:
  - The `chrome.tabs.query` API fetches the active tab's URL and adds it to the list.

---

## Installation
1. Clone or download this repository.
2. Open **Chrome** and navigate to `chrome://extensions`.
3. Enable **Developer Mode** (toggle in the top right corner).
4. Click **Load Unpacked** and select the folder containing the extension's files.

---

## Files
- `index.html`: The user interface.
- `script.js`: Main JavaScript file with functionality.
- `style.css`: Optional styling for the UI.

---

Enjoy seamless lead tracking with Lead Tracker! 