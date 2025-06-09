# Portfolio Project: Marriott Bonvoy Hotels and Villas

## Overview

This project was developed as part of the **Global Career Accelerator (GCA)** program. It is an interactive web-based destination recommendation tool designed to help users find ideal travel spots based on their preferences—whether they're craving a **city**, **beach**, or **mountain** escape.

The application dynamically filters and displays a curated list of recommendations, integrating with an interactive map to enhance user experience. It was built using **vanilla JavaScript**, **HTML/CSS**, and the **OpenLayers API**.

### Built with

* [![JavaScript][JavaScript]][JavaScript-url]
* [![HTML5][HTML5]][HTM5-url]
* [![CSS][CSS]][CSS-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* Open Layers API (for map integration)


## Prototype and Research

Before development, I created an interactive prototype using Google Slides to map out key user flows and refine the selection process. [View the Prototype](https://docs.google.com/presentation/d/1WK8eNRYptK6cHOYqoHHwYMWEAEdfzQ4RAVZfAld4xhU/present?slide=id.g34b949d24ef_0_299)  

For more details on my research and user persona work, see [`marketUsersPrototype.md`](marketUsersPrototype.md).

## My Project Contributions

I was responsible for implementing the core JavaScript logic in `script.js`, which includes:

- **User Preference Filtering**  
  Filters destination data based on the user's choice (city, beach, or mountain) to generate personalized results.

- **Dynamic Destination Cards**  
  Uses DOM manipulation to create visually rich cards showing the destination’s name, location, and image.

- **Interactive Recommendations Display**  
  Injects filtered destinations into the recommendation section and links each card to the map for live location highlighting.

## Features

- **Startup Modal**  
  Prompts users to select their preferred destination type when the page loads.

- **Tailored Results**  
  Displays only destinations that match the selected travel preference.

- **Interactive Map**  
  Clicking a recommendation zooms the map to the relevant location using OpenLayers.

## Project Files

- `index.html` – Main page structure  
- `style.css` – Custom styling  
- `script.js` & `provided.js` – Core logic and dynamic rendering  
- `places.js` – Data source for destination filtering  
- `marketUsersPrototype.md` – User research and prototype planning

## How to Run the Project Locally

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/gca-marriott-bonvoy-website.git
   ```

2. **Navigate into the project folder**  
   ```bash
   cd gca-marriott-bonvoy-website
   ```

3. **Open `index.html` in your browser**  
   You can double-click the file or use a live server to launch it.

## Acknowledgments

The initial concept and structure of this project were based on the Global Career Accelerator program's assignment.


[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[HTML5]: https://img.shields.io/badge/HTML5-FFC9BD?style=for-the-badge&logo=HTML5&logoColor=E34F26
[HTM5-url]: https://developer.mozilla.org/en-US/docs/Web/HTML
[CSS]: https://img.shields.io/badge/CSS-D1BDFF?style=for-the-badge&logo=CSS&logoColor=663399
[CSS-url]: https://developer.mozilla.org/en-US/docs/Web/CSS
[JavaScript]: https://img.shields.io/badge/JavaScript-1d5991?style=for-the-badge&logo=JavaScript&logoColor=F7DF1E
[JavaScript-url]: https://javascript.info/