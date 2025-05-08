# GitHub Followers Viewer

This is a simple web application that displays the followers of a GitHub user. After entering a username, it fetches data from the GitHub API and displays each follower in a card format. It also includes a live search/filter feature to find specific followers by their username.

## 🚀 Demo

Check out the live demo: [https://nursaadet.github.io/Github-Followers/](https://nursaadet.github.io/Github-Followers/)

## 🧑‍💻 Author

[@nursaadet](https://github.com/nursaadet)


## 🚀 What I Used

### 🧠 JavaScript (ES6+)
- **Asynchronous Programming:**
  - Used `async/await` to fetch data from the GitHub API.
  - Implemented error handling using `try/catch` to display custom error messages.

- **DOM Manipulation:**
  - Used `getElementById`, `querySelector`, and `addEventListener` to interact with the HTML.
  - Dynamically generated HTML using `innerHTML`.
  - Controlled element visibility using inline styles (`element.style = "display:none;"`).

- **Event Handling:**
  - Managed user interactions through `click`, `input`, and `load` events.
  - Reset UI on each search and validated user input.

- **Array Methods:**
  - Used `forEach` to loop through follower data and render cards.
  - Applied `filter`, `includes`, and `toLowerCase` to implement case-insensitive live search.

### 🌐 API Integration
- Fetched data from the GitHub API using:
https://api.github.com/users/{username}/followers?per_page=100


### 🎨 Styling with Bootstrap
- Applied Bootstrap classes for layout and styling:
- `card`, `btn btn-dark`, `col`, `text-center`, `text-danger`, etc.
- Created responsive and clean UI components.


## ⚙️ How to Use
1. Open the HTML file in a browser.
2. Enter a GitHub username.
3. View the list of followers.
4. Use the input field to filter followers by username.

## 📝 Notes
- The search input is only shown if the user has followers.
- If no username is entered, an alert is displayed.
- If the user is not found, an error message is shown.

---

This project is a good practice for beginners to learn frontend development and API integration using JavaScript and Bootstrap.

