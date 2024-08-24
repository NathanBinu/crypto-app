# Project Plan for Crypto-App

## Components
- **Header**: Contains the title of the application and any navigation links.
- **CryptoList**: Displays a list of cryptocurrencies with their current prices.
- **CryptoItem**: A sub-component used by `CryptoList` to render individual cryptocurrency details.
- **SearchBar**: Provides a search input to filter cryptocurrencies by name.

## API Integration
- Use the CoinGecko API to fetch real-time cryptocurrency data.
- Example endpoints to use:
  - `GET /coins/markets`: Fetch market data for cryptocurrencies.

## State Management
- Use React’s built-in `useState` and `useEffect` hooks for local component state.
- Consider using Context API if global state management is required.

## Milestones
- **Milestone 1**: Basic UI setup with hardcoded data.
- **Milestone 2**: Integrate the CoinGecko API for live data fetching.
- **Milestone 3**: Implement search functionality.
- **Milestone 4**: Add real-time updates and improve styling.
- **Milestone 5**: Implement user authentication for personalized features.

