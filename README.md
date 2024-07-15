# Progress Steps

A simple project to create progress steps that can be used in multi-level forms or shopping carts. This project was built by following a Udemy tutorial called "50 Projects In 50 Days - HTML, CSS & JavaScript" by Brad Traversy and Florin Pop, with some tiny modifications for this version.

## Table of Contents
- [Description](#description)
- [Modifications](#modifications)
- [Live Demo](#live-demo)
- [Screenshot](#screenshot)
- [Usage](#usage)
- [Project Timeline](#project-timeline)
- [To-Do](#to-do)
- [Credits](#credits)
- [License](#license)
- [Versioning](#versioning)

## Description

This project demonstrates how to create a progress bar with multiple steps, commonly used in multi-step forms or shopping carts. Users can navigate through the steps using 'Next' and 'Previous' buttons. The project starts at step one, and the progress bar updates visually as users navigate through the steps. This project was created by following the second video in the Udemy tutorial "50 Projects In 50 Days" titled "Day 2 - Progress Steps". While the core functionality follows the tutorial, a few minor modifications have been made for this version.

## Modifications

- **CSS**: Added `*::before, *::after` for the `box-sizing: border-box;` declaration on the universal selector.
- **JavaScript**:
  1. Renamed the `update` function to `updateProgress` for better clarity.
  2. Changed the variable names for the buttons to `prevBtn` and `nextBtn` instead of `prev` and `next` for readability.
  3. Introduced the `progressWidth` variable to separate the width calculation from its application to the progress bar for improved code clarity.

## Live Demo

Check out the live version of this project here: [Progress Steps Demo](https://chris-cartaya.github.io/02-progress-steps/)

## Screenshot

!['Progress Steps' Screenshot](images/screenshot.png)

## Usage

Feel free to use this project as a reference for your own HTML, CSS, and JavaScript projects or as a starting point for further modifications.


## Project Timeline

- **Start Date:** July 14, 2024
- **Completion Date:** TBD
- **Last Modified:** July 14, 2024

<!-- 
## To-Do

- [ ] Example. Increase the opacity transition duration for text on mobile devices to prevent the text from looking like it’s falling down as the panel opens. 
-->

## Credits

- [50 Projects In 50 Days &ndash; Brad Traversy and Florin Pop](https://www.udemy.com/course/50-projects-50-days/?couponCode=LETSLEARNNOWPP)

## License

This project is licensed under the MIT License. See the [LICENSE.md](./LICENSE.md) file for details.

## Versioning

### Version 1.0.0
- Initial release.
