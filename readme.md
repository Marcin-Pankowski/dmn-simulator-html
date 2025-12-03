![www.piu.de](img/logo.png)

# DMN Simulator (HTML)

This project provides a simple browser-based DMN (Decision Model and Notation) simulator as a single `dmn-simulator.html` file. It is intended for quickly trying out and debugging DMN decision tables without installing additional tooling.

## Features
- Load and view DMN decision tables in the browser
- Evaluate decisions with custom input data
- Display results directly in the page
- Pure HTML/JS solution – no server required

## Preview

Below is a sample screenshot of the simulator UI:

![DMN Simulator Screenshot](img/screenshot.png)

## Getting Started

1. Clone or download this repository.
2. Open `dmn-simulator.html` in a modern web browser (Chrome, Firefox, Edge, Safari).
3. Use the interface to load your DMN model and run simulations.

## Usage

- Open the file via double-click or drag it into a browser window.
- Follow the on-screen controls to:
	- Import a DMN model
	- Configure or enter input data
	- Execute decisions and inspect the result table

> Note: If your browser blocks local file access, you may need to start a simple local web server (for example with `python -m http.server`) and open the file through `http://localhost:8000/`.

## Requirements

- A modern desktop browser with JavaScript enabled
- DMN model files compatible with the simulator

## Project Structure

- `dmn-simulator.html` – main HTML file containing the simulator
- `img/logo.png` – project logo for documentation and UI
- `img/screenshot.png` – example screenshot of the simulator

## License

This project is licensed under the MIT License.  
Copyright (c) 2025 Marcin Pankowski

See the `LICENSE` file for the full license text.

Have fun your G.O.D. of DMN

www.piu.de
