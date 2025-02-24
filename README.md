# React Router v6 Catch-all Route (*) Issue

This repository demonstrates a common issue encountered when using catch-all routes (*) in React Router v6. The catch-all route, intended to handle any unmatched paths, is not functioning correctly.

## Problem

The provided code uses a catch-all route (`/*`) to display a '404 Not Found' component when the user navigates to a non-existent route. However, the catch-all route doesn't work as expected and the user sees an error instead of the '404' page.

## Solution

The solution involves verifying route configuration and the placement of the catch-all route within the `Routes` component. The catch-all route must be placed as the last route defined within the `Routes` component to ensure that it captures any unmatched paths correctly.  Incorrect placement or other route configuration issues can cause this behavior.

## Setup

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install the dependencies.
4. Run `npm start` to start the development server.