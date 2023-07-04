# FactZone WebApp

FactZone WebApp is a web application that utilizes the News Org API to fetch and display news articles. The application is built using Bootstrap for responsive and user-friendly UI design.

## Features

- Fetches news articles from the News Org API.
- Displays the headlines, descriptions, and images of the news articles.
- Allows users to search for specific news topics.
- Provides filters to sort articles based on different categories.
- Enables users to read the full article by clicking on a specific news item.

## Technologies Used

- HTML5
- CSS3
- Bootstrap
- JavaScript
- News Org API

## Setup and Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/factzone-webapp.git
```

2. Open the project directory:

```bash
cd factzone-webapp
```

3. Run the application on a local server. You can use Python's built-in HTTP server or any other web server of your choice. For example, using Python:

```bash
python -m http.server
```

4. Open a web browser and visit `http://localhost:8000` to see the FactZone WebApp in action.

## Configuration

To make API requests to the News Org API, you will need to obtain an API key. Follow these steps to configure the application with your API key:

1. Go to the [News Org API website](https://newsapi.org/) and sign up for an account.
2. Once logged in, navigate to the "API Keys" section and generate a new API key.
3. Copy the generated API key.
4. Open the `script.js` file in the project directory.
5. Locate the following line of code:

```javascript
const apiKey = 'YOUR_API_KEY';
```

6. Replace `'YOUR_API_KEY'` with your actual API key.

## Usage

Upon opening the FactZone WebApp, you will be presented with a list of news articles fetched from the News Org API. You can browse through the headlines and descriptions of the articles.

To search for specific news topics, use the search bar located at the top of the page. Enter your desired keyword or phrase and press Enter. The application will display the articles related to your search query.

Additionally, you can utilize the provided filters to sort articles by different categories such as business, entertainment, health, science, sports, technology, etc.

To read the full article, simply click on a specific news item. This will open a new tab or window, redirecting you to the source website where the article is published.

## Contributing

Contributions are welcome! If you'd like to contribute to FactZone WebApp, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your forked repository.
5. Submit a pull request explaining your changes.

## License

The FactZone WebApp is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgments

The FactZone WebApp utilizes the News Org API to provide up-to-date news articles. We would like to express our gratitude to the developers and maintainers of the News Org API for their valuable service.

## Contact

If you have any questions, suggestions, or feedback, please feel free to contact us at factzone@example.com.

Thank you for using FactZone WebApp!
