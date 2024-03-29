
# Basic Nui React TypeScript Script Template

This script is a basic and essential implementation for creating a Native User Interface (NUI) in FiveM. It provides the foundation for integrating web-based UI elements seamlessly into your FiveM server.


## Features

- Simple and lightweight implementation
- Easy to customize and extend
- Well-documented code for better understanding

## REQUIREMENTS
* [Node > v10.6](https://nodejs.org/en/)

*A basic understanding of React TypeScript, If you don't understand it, React may not be for you yet.*




## Installation

1. write in terminal:

```bash
    cd web
    npm i
```

2. Download the `basicNuiReact` folder.
3. Place the `basicNuiReact` folder in your FiveM server's `resources` directory.
4. Add `start basicNuiReact` to your server.cfg file. or use `refresh`, and `start basicNuiReact` in the server console
5. If you chose to add that line to your server.cfg, Restart your FiveM server.


## Usage/Examples

inside the game you can write in the chat /show-ui, and the website will be shown on the screen

- In order to modify the website in react, within visual studio code, for example, you will have to modify the src components, and once you have everything prepared, you will only have to write this in a terminal:

```bash
    cd web
    npm run build
```

- and then restart the server, or use the `refresh` command, and restart `basicNuiTypescript` in the server console

## Screenshots

- typing `show-ui` in the chat, our website will appear.
![Screenshot 01](https://raw.githubusercontent.com/CreztY/basicNuiTypescript/main/preview/01.png)

- by pressing the `ESC` key, it will stop showing our website
![Screenshot 01](https://raw.githubusercontent.com/CreztY/basicNuiTypescript/main/preview/02.png)

## Author

- [@CreztY](https://www.github.com/CreztY)

