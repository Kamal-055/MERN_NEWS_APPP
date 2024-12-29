# MERN News App

The MERN News App is a full-stack web application that allows users to browse, search, and filter the latest news articles by category or keyword. Built using the MERN stack (MongoDB, Express.js, React, and Node.js), it provides a seamless user experience with real-time updates from a news API.

## Features

- Browse News: View the latest news articles from multiple categories.
- Search: Search for articles by keywords.
- Filter by Category: Filter news by predefined categories like Sports, Technology, Health, etc.
- Real-Time Updates: Fetch and display the latest news dynamically using a news API.

## Tech Stack

### Frontend:
- React: For building the user interface.
- React Router: For navigation between pages.
- Axios: For making API requests.

### Backend:
- Node.js: For running the server.
- Express.js: For handling routes and middleware.
- MongoDB: For storing user preferences (optional, if implemented).

### API:
- News API: Used to fetch the latest news articles.

## Installation

### Prerequisites
- Node.js and npm installed on your machine.
- MongoDB installed or access to a cloud MongoDB service (e.g., MongoDB Atlas).

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/kamal-055/mern-news-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd mern-news-app
   ```

3. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```

4. Install dependencies for the frontend:
   ```bash
   cd ../frontend
   npm install
   ```

5. Create a `.env` file in the `backend` directory and add the following:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   NEWS_API_KEY=your_news_api_key
   ```

6. Start the backend server:
   ```bash
   cd ../backend
   npm start
   ```

7. Start the frontend server:
   ```bash
   cd ../frontend
   npm start
   ```

8. Open your browser and navigate to `http://localhost:3000` to use the app.

## Folder Structure

```
mern-news-app/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── .env
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   ├── index.js
│   └── package.json
└── README.md
```

## API Usage

The app uses the [News API](https://newsapi.org/) to fetch the latest news. You need to sign up for an API key and add it to the `.env` file in the backend directory.

## Deployment

### Frontend:
- Deploy the React app to a platform like [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/).

### Backend:
- Deploy the Node.js server to a platform like [Heroku](https://www.heroku.com/) or [Railway](https://railway.app/).

### Environment Variables:
Ensure that the environment variables (e.g., API keys, MongoDB URI) are configured properly in your deployment platform.

## Contributing

Contributions are welcome! Please fork this repository and create a pull request for any changes you'd like to make.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [News API](https://newsapi.org/) for providing real-time news data.
- MERN stack community for excellent tools and resources.
