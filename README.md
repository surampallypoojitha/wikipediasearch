Wikipedia Search Web Application 🔍
📖 Overview

This project is a Wikipedia Web Search Application that allows users to search for any topic and instantly retrieve relevant Wikipedia articles. The app interacts with a public API, displays results dynamically, and provides direct links to full Wikipedia pages.

The application focuses on simplicity, speed, and usability, making it ideal for beginners learning web development and API integration.

✨ Features

🔎 Search Wikipedia articles by keyword

⚡ Real-time API-based search results

⏳ Loading spinner while fetching data

🔗 Clickable article titles and URLs

📱 Responsive design using Bootstrap

🧹 Automatically clears old results on new search

🧱 Project Structure
wikipedia-search-app/
  index.html     # Structure of the web page
  styles.css     # Styling and layout
  script.js      # Application logic and API handling
  README.md      # Project documentation

🧠 How the Application Works
1️⃣ User Input

The user types a keyword into the search bar.

Pressing Enter triggers the search event.

2️⃣ API Request

JavaScript captures the input and sends a GET request to:

https://apis.ccbp.in/wiki-search?search=<keyword>

3️⃣ Loading Indicator

A spinner appears while the data is being fetched.

This improves user experience by showing progress.

4️⃣ Display Results

The response is parsed from JSON.

Each result shows:

Article Title

Wikipedia URL

Short Description

5️⃣ External Navigation

Clicking a title or link opens the article in a new browser tab.

🛠️ Technologies Used
🔹 HTML

Defines the structure of the application

Input field, container, result sections

🔹 CSS

Custom styling for layout and readability

Google Fonts for clean typography

Bootstrap utility classes for responsiveness

🔹 JavaScript

DOM manipulation

Event handling (keydown)

API fetching using fetch()

Dynamic creation of search result elements

🔹 Bootstrap

Responsive grid and layout

Spinner component

Mobile-friendly UI

🚀 Advantages & Benefits

✅ Beginner-friendly project

✅ Demonstrates real-world API usage

✅ Clean separation of HTML, CSS, and JS

✅ No backend required

✅ Fast and lightweight

✅ Improves understanding of asynchronous JavaScript

📈 Learning Outcomes

By building this project, you learn:

API integration using JavaScript

Handling user input events

DOM manipulation

Fetching and displaying dynamic data

UI/UX improvement using loaders and layouts

🌱 Future Enhancements

🔄 Search on button click

🌙 Dark mode support

📌 Search suggestions

❌ Error handling for empty searches

📄 Pagination for large results

📂 How to Run

Clone the repository

Open index.html in a browser

Type a keyword and press Enter

🙌 Conclusion

This Wikipedia Search Application is a clean, functional, and practical example of modern web development fundamentals. It showcases how frontend technologies work together to build interactive, real-time applications.
