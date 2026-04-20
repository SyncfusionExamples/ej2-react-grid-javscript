# React Grid Sample using Syncfusion

## Repository Description

This repository demonstrates a simple React application that uses the Syncfusion Essential JS 2 React Grid component to display tabular data with paging support.

## Project Overview

This project is a sample implementation of the Syncfusion EJ2 React Grid integrated into a React application. The grid is configured to display order-related data such as Order ID, Customer ID, Employee ID, Freight cost, and Shipping Country. It showcases how to bind a local data source to the grid and define columns declaratively using Syncfusion’s GridComponent and related directives.

The application is built using React class components and leverages Syncfusion’s paging service to improve data navigation. This example is intended for learning and demonstration purposes, helping developers understand basic grid configuration, column mapping, and service injection in a React environment.

## Features

- Displays structured order data in a tabular grid
- Column configuration using ColumnsDirective and ColumnDirective
- Built-in paging enabled using Syncfusion Page service
- Currency formatting for numeric columns
- Simple and clean React component structure

## Technologies Used

- React
- Syncfusion Essential JS 2 React Grid
- JavaScript (ES6)

## Usage

The Grid component is rendered inside the main App component and is bound to a static data array. Paging is enabled by injecting the Page service, and each column is mapped to a specific data field.

## Running the Application

Follow these steps to run the application locally:

1. Clone the repository:
    ```
    git clone <repo_link>
    ```
2. Install the dependencies and run the application:
    ```
    npm i
    npm start
    ```
The application will be available at `http://localhost:3000`.


## Reference Documentation & Demo Links

- [Syncfusion React Grid Documentation](https://ej2.syncfusion.com/react/documentation/grid/getting-started/)
- [Paging](https://ej2.syncfusion.com/react/documentation/grid/paging)
- [React version compatibility](https://ej2.syncfusion.com/react/documentation/upgrade/version-compatibility)
- [Syncfusion React Grid Online Demos](https://ej2.syncfusion.com/react/demos/#/material/grid/overview)
- [Syncfusion NPM Package](https://www.npmjs.com/package/@syncfusion/ej2-react-grids)
