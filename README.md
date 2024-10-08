# Timezone Converter

## Overview

The Timezone Converter is a web application that allows users to easily convert current time between different time zones. It includes features such as adding, removing, and reordering time zones, a date picker, dark mode toggle, Google Meet scheduling, and a timezone slider for selecting and adjusting time across different zones. The application is responsive and designed to provide an intuitive user experience with a focus on real-time updates and attractive, animated visuals.

## Features

- **Add/Remove Timezones**: Easily add or remove time zones from your list.
- **Reorder Timezones**: Drag and drop to reorder time zones as needed.
- **Date Picker**: Select a specific date to see time conversions for that day.
- **Dark Mode Toggle**: Switch between light and dark modes for better visibility and aesthetics.
- **Google Meet Scheduling**: Quickly schedule Google Meet meetings based on the selected time zones.
- **Timezone Slider**: Adjust the time in different time zones using an interactive slider.
- **Share Functionality**: Share your configured time zones with others via a public URL.
- **Responsive Design**: The layout adapts to both laptop and mobile displays, ensuring a seamless experience on any device.
- **3D Animation Effects**: The application includes 3D effects and animations for a visually stunning experience.
- **Attractive UI/UX**: Carefully designed interface with animated elements, ensuring a delightful user experience.

## File Structure

```plaintext
timezone-converter/
│
├── public/
│   ├── index.html
│   └── ...
│
├── src/
│   ├── App.js
│   ├── index.js
│   └── global.css
│
└── README.md
```

### Components

- **`Navbar.js`**: The navigation bar with animated elements to enhance the UI/UX.
- **`TimezoneConverter.js`**: The main component that handles the logic for time zone conversion, with 3D effects.
- **`TimezoneCard.js`**: Individual time zone cards, designed to be attractive and animated.
- **`TopSection.js`**: The top section containing date picker, dark mode toggle, and other controls arranged horizontally.
- **`Footer.js`**: An attractive, center-aligned footer with animated effects, ensuring it doesn't overlap with main content.

### Utilities

- **`utils.js`**: Utility functions for time zone calculations, date formatting, and other helper functions.

### Global Styles

- **`global.css`**: Contains global CSS styles, including responsive design rules, animations, and custom styles for dark mode.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/timezone-converter.git
   cd timezone-converter
## Install Dependencies
```bash
npm install
```
## Run the Application
```bash
npm start
```
##  Build for Production
```bash
npm run build
```

## Usage

- **Adding Timezones**: Click the "Add Timezone" button and select a time zone from the list.
- **Reordering Timezones**: Drag and drop the time zone cards to reorder them.
- **Date Picker**: Use the date picker to choose a date and see the corresponding times.
- **Dark Mode**: Toggle the dark mode switch to change the theme.
- **Google Meet Scheduling**: Click on the "Schedule Meet" button to set up a Google Meet.
- **Timezone Slider**: Use the slider to adjust and compare times across different zones.
- **Sharing**: Click the "Share" button to generate a public URL for your current configuration.

## Contributing
- **Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your changes.**

- 
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- **Varri Sai Pradeep**
- **Email**: your-email@example.com
- **Phone**: +917997930250
