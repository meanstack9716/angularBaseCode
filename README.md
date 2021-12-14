This is a sample angular Structure for Large Application.

# Project Structure

- app
  -- core
  -- features
  -- shared
  -- styles
  -- assets

## Core Folder and Module

The core folder and module contain shared singleton services and app-level components. The top-level App module uses these App-level components—for example, a navigation component. Creating a Core folder and module prevents your main application folder from becoming too cluttered.

## Shared Folder And Module

The shared module contains components, pipes, and directives used and referenced by components in feature modules.

## The Feature Folder and Modules

All Other modules

## Styles & Assets

The styles folder contains all the global style sheets of your application. The assets folder contains all the images, vectors, and other types of your application assets.
