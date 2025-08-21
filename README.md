Top 100 Crypto Dashboard
This is a clean, fast, and minimalist single-page application (SPA) designed to track the top 100 cryptocurrencies by market capitalization. It was built as a modern web application, prioritizing a seamless user experience on both desktop and mobile devices.

Key Features
Live Data: Displays real-time data for the top 100 cryptocurrencies, including rank, name, price, market cap, and trading volume.

Dynamic Sorting: Users can sort the main table by various metrics like price, market cap, or percentage change to quickly find the information they need.

Currency Selector: The application supports multiple currencies (EUR, USD, GBP, JPY, AUD), allowing users to view all data in their preferred currency.

Interactive Graphs: Clicking on any cryptocurrency in the table opens a pop-up modal with a detailed price chart. The chart is interactive and allows users to view data over different timeframes (1D, 7D, 1M, 1Y, All).

Responsive Design: The layout automatically adjusts to the screen size. On mobile devices, the data is displayed in a user-friendly card format instead of a compressed table.

Dark Mode Toggle: A simple toggle in the header allows users to switch between light and dark themes for comfortable viewing in any environment.

News Feed: A collapsible section at the bottom of the page displays the latest crypto-related headlines in an elegant card layout. It includes a "Go to News" button in the header for easy navigation.

Client-Side Caching: The application caches data locally to minimize API calls and improve performance and load times.

Tech Stack
This project is built with a simple and lightweight tech stack to ensure speed and efficiency:

Frontend: Pure HTML5, CSS3, and JavaScript.

External Libraries:

Chart.js and Luxon.js: Used for rendering the interactive, responsive price graphs.

Google Fonts (Inter): Provides a modern and clean typeface for the website.

APIs:

CoinGecko API: Fetches real-time cryptocurrency market data and historical price information.

RSS2JSON API: A public proxy service used to convert a crypto news RSS feed into a usable JSON format.

Future Improvements
Watchlist: A feature to allow users to save their favorite coins to a personalized list using local storage.

Portfolio Tracker: An interface where users can manually input their crypto holdings to calculate and track their total portfolio value.

More News Sources: Expand the news feed to pull from multiple, customizable sources.
