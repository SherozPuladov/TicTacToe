# TicTacToe

A simple Tic-Tac-Toe game created to test how **Blazor WebAssembly** works on .NET 6.

The project is implemented as a SPA application using Blazor WASM without any third-party libraries. The main goal was to explore the component lifecycle, data binding, event handling, and UI re-rendering.

## Technologies

- Blazor WebAssembly  
- .NET 6 (`net6.0`)  
- C#  
- Razor Components  

Used packages:

- `Microsoft.AspNetCore.Components.WebAssembly` (6.0.14)  
- `Microsoft.AspNetCore.Components.WebAssembly.DevServer` (6.0.14)  

## Features

- 3x3 game board  
- Alternating turns between X and O  
- Win detection  
- Draw detection  
- Move blocking after the game ends  
- Game restart functionality  

## Screenshots

### Empty Board

![Empty Board](./Screenshots/TicTacToe.png)

### O Wins

![O Wins](./Screenshots/TicTacToeOWin.png)

### X Wins

![X Wins](./Screenshots/TicTacToeXWin.png)

### Draw

![Draw](./Screenshots/TicTacToeDraw.png)

## Run the Project

```bash
dotnet restore
dotnet run
````

The application runs using the built-in DevServer and opens in the browser.

## Project Purpose

This project was created as a learning experiment to understand:

* Blazor WASM architecture
* Component development
* Client-side state management
* User input handling
* Rendering logic without JavaScript