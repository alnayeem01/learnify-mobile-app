# Learnify — React Native Learning App

A mobile learning application built with **React Native and TypeScript**, focused on delivering course content and supporting common learning workflows on mobile.

This project was built as a full-stack application, with a separate backend API and a React Native client.

## Features

- Mobile learning interface
- Course/content browsing
- User authentication and API integration
- Form handling and validation
- Media and document-related functionality
- Client-side state and server-state management
- Responsive React Native UI

## Tech Stack

- **React Native**
- **TypeScript**
- **Redux Toolkit** — application state
- **TanStack React Query** — server state and API data
- **Axios** — HTTP client
- **Formik + Yup** — forms and validation
- **React Navigation** — navigation
- **AsyncStorage** — local persistence
- **React Native Reanimated** — animations

## Architecture

```text
React Native mobile app
        ↓
     Axios API client
        ↓
   Learnify backend
        ↓
     Database
```

Backend repository: https://github.com/alnayeem01/learnify-server

## Running locally

Make sure the React Native development environment is configured for your platform.

```bash
npm install
npm start
```

Then run the application on Android or iOS using the React Native CLI:

```bash
npm run android
```

or

```bash
npm run ios
```

## Project focus

This project demonstrates practical React Native development beyond a basic UI, including API integration, authentication-related flows, state management, forms, media handling and mobile navigation.

## Status

Learning/project application. Built as part of my development work while expanding into React Native and mobile product development.
