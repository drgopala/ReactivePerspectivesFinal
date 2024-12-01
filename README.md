# National Parks Showcase

## Overview
This project is a React-based National Parks Showcase website that dynamically displays information about various U.S. national parks. The website includes a carousel of park images, a modal for more details about each park, and an accordion to reveal additional park information. It is built with a focus on responsive design and user-friendly interaction.

## Features
- **Carousel:** A sliding image gallery of national parks with navigation controls.
- **Accordion:** Allows users to toggle additional information about each park (e.g., location, establishment date, and notable features).
- **Modal:** Displays additional park information, including a link to the official website for each park, when clicked.
- **Responsive Design:** The site adjusts layout and components for optimal viewing across various screen sizes, utilizing Tailwind CSS for styling.

## Key Technologies
- **React**: For building the components and managing state.
- **React Hooks**: Used to manage component state and handle interactions.
- **Tailwind CSS**: For responsive and utility-first styling.
- **Props**: Data for each park is passed to components via props for dynamic content rendering.
- **State Management**: React `useState` hook is used to control the visibility of modals and the active index of the carousel.

## Components
- **Carousel**: Displays a series of images related to each park. The carousel updates dynamically when navigating between parks.
- **LearnMoreModal**: A modal component that pops up when the user clicks the "Learn More" button, displaying detailed park information and a link to the official website.
- **Accordion**: Used to show additional information about the park such as location, establishment date, and notable features. It dynamically adjusts based on the selected park.
- **Header, Footer, and Main Pages**: Provide the basic structure and navigation for the site.

## Responsiveness
The website is designed to be fully responsive. The layout adjusts using Tailwind's utility classes, such as `sm:`, `md:`, and `lg:` to change the component styles based on the screen size. This ensures the components look great on all devices, from mobile phones to large desktop screens.

## Performance
- **Efficient Rendering**: Only the relevant components are re-rendered when needed, thanks to React's efficient diffing algorithm.
- **Conditional Rendering**: Modals and accordions are conditionally rendered to improve performance, reducing unnecessary DOM elements.
- **React Hooks**: We use React’s `useState` to handle local state efficiently, ensuring smooth user interactions without unnecessary rerenders.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/national-parks-showcase.git
