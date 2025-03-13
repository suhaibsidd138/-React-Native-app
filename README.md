# React Native User Information App

A simple React Native application that displays user information fetched from a public API. This app showcases navigation between user profiles with previous and next buttons.

## Features

- Displays detailed user information including ID, UID, password, first name, last name, username, email, and avatar
- Navigation between users with Previous and Next buttons
- Handles 80 users of data fetched from the Random Data API
- Clean and responsive UI
- Error handling and loading states

## Screenshots

[Add screenshots of your app here]

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/react-native-user-info-app.git
   cd react-native-user-info-app
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the Metro bundler:
   ```bash
   npx react-native start
   # or
   yarn start
   ```

4. Run the application:
   
   For Android:
   ```bash
   npx react-native run-android
   # or
   yarn android
   ```
   
   For iOS:
   ```bash
   npx react-native run-ios
   # or
   yarn ios
   ```

## Project Structure

```
src/
  ├── App.js          # Main application component
  └── assets/         # Images and other static assets
```

## Technical Details

- Built with React Native
- Fetches user data from the Random Data API
- Implements navigation between user profiles
- Handles loading states and errors gracefully
- Responsive design that works on various device sizes

## API Used

This app uses the Random Data API to fetch random user information:
```
https://random-data-api.com/api/users/random_user?size=80
```

## Additional Notes

- The app fetches 80 users at once to minimize API calls and ensure smooth navigation
- Error handling is implemented to provide a good user experience even when network issues occur
- UI is designed to be clean and intuitive

## Future Improvements

- Add search functionality to find specific users
- Implement user favorites
- Add filtering options
- Store data locally for offline access

## License

[MIT License](LICENSE)
