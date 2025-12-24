# My Movie Search Website

<img width="1385" height="1000" alt="Image" src="https://github.com/user-attachments/assets/6d2a38e4-e3c1-46f1-b23e-8f1f9104770d" />

> > A dynamic movie search application built with React, allowing users to search for movies via the OMDb API and view detailed information.

**Live Demo:** **Live Demo:** [arminshami7.github.io/movie-search-app](https://arminshami7.github.io/movie-search-app/)

---

## 🚀 Features

-   **Dynamic Search:** Search for movies in real-time using the OMDb API.
-   **Multi-Page Navigation:** Seamlessly navigate between the search page and movie detail pages without page reloads, thanks to React Router.
-   **Detailed Movie View:** Click on any movie to see its detailed information, fetched dynamically based on the URL parameter.
-   **Robust UI States:** Clear feedback is provided to the user for loading, error, and no-result states.
-   **Responsive Design:** The interface is fully responsive and works well on desktops, tablets, and mobile devices.

---

## 🛠️ Tech Stack & Tools

This project was built using the following technologies:

-   **Front-End:**
    -   [**React.js**](https://reactjs.org/): A JavaScript library for building user interfaces.
    -   [**Vite**](https://vitejs.dev/): A modern and fast build tool for web development.
    -   [**Tailwind CSS**](https://tailwindcss.com/): A utility-first CSS framework for rapid UI development.
-   **Routing:**
    -   [**React Router**](https://reactrouter.com/): For declarative routing in a single-page application.
-   **Deployment:**
    -   [**GitHub Pages**](https://pages.github.com/): For hosting the static site.
    -   [**GitHub Actions**](https://github.com/features/actions): For automating the build and deployment process (CI/CD).```
-   **Version Control:**
    -   [**Git & GitHub**](https://github.com/arminshami7/front-end/tree/main/docs/projects/movie-search-app): For source code management.

---

## 📝 What I Learned

This project was my first deep dive into building a data-driven, multi-page application with React. It was a crucial step in my learning journey, and here are the key skills I developed:

-   **Working with External APIs:** I learned how to make asynchronous requests to a real-world API (OMDb API) using `fetch` and `async/await` inside a `useEffect` hook.

-   **Advanced State Management:** I went beyond simple `useState` and learned to manage multiple states simultaneously, including `isLoading`, `error`, and the fetched data itself. This taught me how to create a robust and user-friendly experience by handling all possible UI states.

-   **Dynamic Routing with React Router:** This was my first experience with dynamic routes. I learned how to create routes with parameters (e.g., `/movie/:id`) and use the `useParams` hook to fetch and display data for a specific item.

-   **Component-Based Architecture:** I practiced breaking down the UI into reusable components like `MovieCard`, which made the code cleaner, more organized, and easier to maintain.

-   **Defensive Coding:** I learned to anticipate and handle potential issues, such as API errors or searches with no results, to prevent the application from crashing and provide clear feedback to the user.

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

-   Node.js (v18 or higher)
-   npm

### Installation

1.  Clone the repo
    ```sh
    [**Git & GitHub**](https://github.com/arminshami7/movie-search-app)
    ```
2.  Install NPM packages
    ```sh
    npm install
    ```
3.  Start the development server
    ```sh
    npm run dev
    ```# movie-search-app
# movie-search-app
