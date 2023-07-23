# Analog Clock

This repository showcases the creation of an analog clock using HTML, CSS, and JavaScript. The clock features a classic design with hour, minute, and second hands to display the current time.

## Preview

https://github.com/Rishabh1662/analog-clock/assets/130847211/54111d06-8b58-489d-9d3a-b78aad0178ab

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To view the analog clock locally, follow these steps:

1. Clone the repository: `git clone https://github.com/Rishabh1662/analog-clock.git`
2. Open the project folder.
3. Open the `index.html` file in your preferred browser.

## Implementation Details

In this project, the analog clock was implemented using HTML, CSS, and JavaScript. Here's an overview of how it was achieved:

1. **HTML Structure**: The clock face was created using HTML elements, such as `div` and `span`, to build the clock layout, including the clock hands.

2. **CSS Styling**: CSS was used to style the clock elements, including colors, sizes, and positions. The clock hands were styled to resemble the traditional analog clock design.

3. **JavaScript Interaction**: JavaScript played a pivotal role in updating the clock hands' positions based on the current time. Key JavaScript concepts and features used include:

   - **Get Element by Class Name**: The `getElementsByClassName` method was used to select the clock hands' elements in the HTML, enabling dynamic updates of their positions.

   - **New Date Object**: The `Date` object was utilized to retrieve the current time, allowing for real-time updates of the clock hands.

   - **Audio Alert**: An optional audio alert can be played at every hour, notifying the user of the time change. This was achieved using the `new Audio` object to create an audio element.

4. **Clock Animation**: CSS animations or transitions were used to create smooth movement of the clock hands, producing a realistic analog clock effect.

## Customize Clock

If you wish to customize the clock's appearance or add new features, here are some ideas:

- Change the clock's color scheme and style to match your preferences.
- Implement additional clock hands, such as a second timezone or a day/night indicator.
- Add custom audio alerts or chimes for different events or times.

## Resources

If you're interested in learning more about working with dates in JavaScript or creating animations using CSS, check out the following resources:

- [MDN Web Docs: Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)
- [MDN Web Docs: CSS Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations)
- [MDN Web Docs: CSS Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions)

## License

This project is licensed under the [MIT License](LICENSE).
