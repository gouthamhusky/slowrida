# OpenLibrary Search App

This repository contains a simple, responsive web application built with React, TypeScript, and React-Bootstrap. The application allows users to search for books using the OpenLibrary API, displaying information such as the book's title, author(s), publication year, ISBN, and page count. Users can toggle sorting the results by the year the book was first published.

## Features

- **Instant Search**: Implements auto-search functionality, querying the OpenLibrary API as the user types.
- **Debounced API Calls**: Reduces the frequency of API calls to enhance performance and user experience.
- **Dynamic Sorting**: Users can toggle the sort order based on publication year.
- **Responsive Design**: Utilizes React-Bootstrap for a layout that adjusts to various screen sizes and devices.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **TypeScript**: Adds static types to JavaScript for better maintainability and developer experience.
- **React-Bootstrap**: Provides responsive design components styled with Bootstrap.
- **OpenLibrary API**: Fetches data about books dynamically.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following installed:
- Node.js (version 18.x or later)
- npm (version 9.x or later)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/book-search-app.git
   cd book-search-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Run the application locally**
   ```bash
   npm start
   ```
