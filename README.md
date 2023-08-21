# Brexit Votes React Visualizer

This React application visualizes how MPs voted on 8 key Brexit issues. It represents each MP's vote using a parallel coordinate chart, and provides a searchable interface for users to find their respective MP's vote on each of these issues.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)

## Features

- **Visual Representation**: Display how each MP voted on the eight pivotal Brexit decisions.
- **Search Functionality**: Users can search for their MP and view their respective voting patterns.
- **Responsive Design**: Adapted for different screen sizes.

## Project Structure
```
react-project/
├── public/
│ └── index.html
├── src/
│ ├── assets/
│ │ └── fonts/
│ │ └── search-icon.svg
│ ├── components/
│ │ ├── Chart/
│ │ ├── Dates/
│ │ ├── Header/
│ │ ├── Legend/
│ │ ├── Motions/
│ │ ├── Search/
│ │ └── StickyHeader/
│ ├── data/
│ │ ├── motionsDetails.ts
│ │ ├── mpVoteStats.ts
│ │ ├── partyColourMap.ts
│ │ ├── partyVoteStats.ts
│ │ └── votePlotPoints.ts
│ ├── hooks/
│ │ └── useWindowEvent.ts
│ ├── App.css
│ ├── App.tsx
│ ├── declarations.d.ts
│ └── index.tsx
├── .gitignore
├── package.json
├── package-lock.json
└── tsconfig.json
```



## Getting Started

1. **Install Dependencies**

    ```bash
    npm install
    ```

2. **Run the Application**

    ```bash
    npm start
    ```

   This will launch the development server and open the app in your default browser.