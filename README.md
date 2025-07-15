# MovieMagnet

A modern, feature-rich mobile movie discovery application built with React Native and Expo. MovieMagnet provides a sleek and intuitive interface for browsing, searching, and discovering movies.

## Features

- Browse trending movies
- Advanced movie search with real-time results
- Modern, responsive UI with dark theme
- Movie details with comprehensive information
- Native performance with Expo
- Search history tracking

## Tech Stack

- **Framework**: React Native with Expo
- **Navigation**: Expo Router
- **Styling**: Tailwind CSS
- **Backend**: Appwrite for data storage
- **API**: The Movie Database (TMDB)
- **Type Safety**: TypeScript

## Getting Started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

3. Choose your development environment:
   - Android: Use Android Studio emulator or physical device
   - iOS: Use Xcode simulator or physical device
   - Web: Open in browser

## Project Structure

```
mobile_movie_app/
├── app/
│   ├── (tabs)/
│   │   ├── index.tsx      # Home screen with trending movies
│   │   ├── search.tsx     # Movie search screen
│   │   ├── saved.tsx      # Saved movies screen
│   │   └── profile.tsx    # User profile screen
│   └── movie/[id].tsx     # Movie details screen
├── components/
│   ├── MovieCard.tsx      # Movie display component
│   ├── SearchBar.tsx      # Search functionality
│   └── TrendingCard.tsx   # Trending movies display
├── services/
│   ├── api.ts            # TMDB API integration
│   └── appwrite.ts       # Appwrite backend services
├── interfaces/
│   └── interfaces.d.ts   # TypeScript interfaces
└── tailwind.config.js    # Tailwind CSS configuration
```

## Development

### Prerequisites

- Node.js (v18 or higher)
- Expo CLI
- Android Studio (for Android development)
- Xcode (for iOS development)

### Development Build

```bash
npm run reset-project  # Reset project to initial state
npm install           # Install dependencies
npx expo start        # Start development server
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
