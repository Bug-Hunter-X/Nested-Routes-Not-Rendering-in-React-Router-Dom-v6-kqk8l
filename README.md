# React Router Dom v6 Nested Route Bug

This repository demonstrates a bug encountered when using nested routes in React Router Dom v6.  The nested routes are correctly defined, but they fail to render, causing a 404 error.

## Problem

The primary issue is that nested routes within the application do not render as expected.  The application structure is designed for nested navigation, however the nested routes do not match URLs, always rendering the 404 component.

## Solution

The solution involves carefully checking the route paths for correctness, ensuring that they are properly defined and account for parent route paths.  The solution provided ensures proper URL matching for nested routes.  This was resolved by checking the route paths and handling the nested routes within the parent route component.