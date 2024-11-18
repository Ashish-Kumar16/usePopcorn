# 📽️ usePopcorn: Movie Explorer Application

**usePopcorn** is a React-based movie discovery application that allows users to search for movies, view details, and curate a personal watchlist. The app integrates with the OMDb API to fetch movie data and offers interactive features such as movie ratings, real-time search, and a dynamic user interface.

---

## 🌟 Features

- **Search Movies**: Search for movies by their titles using the OMDb API.
- **Movie Details**: View comprehensive details about a selected movie, including plot, director, actors, IMDb rating, and runtime.
- **Watchlist Management**:
  - Add movies to a personal watchlist.
  - View average IMDb rating, user rating, and total runtime of watched movies.
  - Delete movies from the watchlist.
- **Custom Ratings**: Rate movies with a dynamic star-rating component.
- **Responsive UI**: Expandable sections for toggling visibility of the movie list and watchlist.

---

## 🛠️ Technologies Used

- **Frontend**: React (functional components, hooks)
- **Styling**: CSS
- **API Integration**: OMDb API
- **State Management**: `useState`, `useEffect`, and custom hooks
- **Custom Hooks**:
  - `useKey` for handling global key events.
  - `useLocalStorageState` for persisting watchlist data.
  - `useMovies` for managing movie fetching and state.

---

## 🚀 Getting Started

### Prerequisites

- Node.js installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/usePopcorn.git
   cd usePopcorn
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open the app in your browser:
   ```plaintext
   http://localhost:3000
   ```

---



## 📦 API Integration

This project uses the [OMDb API](http://www.omdbapi.com/) for fetching movie data.  
Replace the API key in the code with your own:

```javascript
const KEY = "your_api_key";
```

---

## 🧑‍💻 Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your feature description"
   ```
4. Push the changes:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Create a pull request.

---

## 📜 License

This project is licensed under the MIT License. Feel free to use and modify it.

---

## 🛡️ Acknowledgments

- **OMDb API**: For providing the movie data.
- **React**: For powering the dynamic and interactive UI.

---

**Happy Watching! 🍿**



<!-- ### 🌟 Features  
1. Search and explore movies using the OMDb API.  
2. Add, manage, and delete movies in a personalized watchlist.  
3. Rate movies with an interactive star-rating system.  
4. View detailed movie information, including plot, IMDb rating, and runtime.  
5. Get watchlist summaries with average IMDb rating, user rating, and total runtime.  

### 🛠️ Technologies Used  
1. **React** for building dynamic user interfaces.  
2. **OMDb API** for fetching real-time movie data.  
3. **Custom Hooks** (`useKey`, `useLocalStorageState`, `useMovies`) for functionality.  
4. **CSS** for responsive and clean styling.  
5. **Local Storage** for persisting watchlist data across sessions.   -->