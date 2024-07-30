<!-- 
- What
- How
- Why
-->

**Overview** <br>
  This project is a simple and interactive Shopping App designed to help users manage their shopping lists. It allows users to add items with details such as name, quantity, and price, and keep track of their purchases. The app uses IndexedDB via Dexie.js for client-side data storage, making it a Progressive Web App (PWA) that can work offline.

**Files** <br>
  - index.html: Main HTML file containing the structure of the web page.
  - index.js: JavaScript file responsible for the app's logic and interactivity.
  - index.css: CSS file defining the styles and layout for the web page.
  - manifest.json: Manifest file for PWA configuration.
  - sw.js: Service worker file for offline capabilities 
  - dexie.min.js: Dexie.js library for handling IndexedDB operations.

**Getting Started** <br>
  To get the Wordle Clone up and running on your local machine, follow these steps:

  1. Clone the Repository <br>
     ```git clone https://github.com/yourusername/shopping-app.git``` <br>
     ```cd shopping-app```

  3. Open the Project in Your Browser <br>
     Simply open the index.html file in your preferred web browser. You can do this by double-clicking the file or using the browser's "Open File" feature.

  4. Start Playing <br>
     Once the page loads, you can start adding items to your shopping list. Enter the item name, quantity, and price, then click "Add item." You can mark items as purchased, and the app will automatically calculate the total price.

**Features** <br>
  - Add Items: Add items with a name, quantity, and price to your shopping list.
  - Update Status: Mark items as purchased and visually distinguish them.
  - Delete Items: Remove items from the list as needed.
  - Total Price Calculation: Automatically calculate and display the total price of all items.
  -Offline Capability: The app works offline thanks to the service worker and IndexedDB.

**Why This App?** <br>
  The primary purpose of creating this Shopping App is to practice and demonstrate skills in HTML, CSS, JavaScript, and working with IndexedDB via Dexie.js. Additionally, it showcases:
  - PWA Implementation: Creating a Progressive Web App that can be used offline.
  - Client-Side Data Storage: Using IndexedDB for storing and managing data on the client side.
  - Interactive UI: Building an interactive user interface with dynamic content updates.
