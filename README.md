# Shape and Color Change Demo

This HTML and JavaScript code demonstrates how to change the background color and shape of a circle using buttons. The code uses basic HTML and CSS for the layout and appearance, and JavaScript for handling the color and shape changes.

## Features

- Change the background color of the circle by clicking the "Change Color" button.
- Toggle between a circle and a triangle shape by clicking the "Change Shape" button.

## Demo

You can see a live demo of the project [here](https://22pankajsahu.github.io/m6Day10ClassChallenge/).

## Screenshots

Include relevant screenshots of the application here.

![image](https://github.com/22pankajsahu/m6Day10ClassChallenge/assets/135128502/a1cf7f06-f320-4779-b82f-984b09405dc0)

![image](https://github.com/22pankajsahu/m6Day10ClassChallenge/assets/135128502/3985ed5f-a64a-4db3-b84f-97a0a51da759)

## How It Works

### HTML Structure

- The code defines a container with two buttons and a circle element.
- The circle element contains a shape element that can be changed to a triangle shape.

### CSS Styling

- The CSS styles define the layout and appearance of the container, circle, and shape elements.
- The `.shape` class represents the square shape, and the `.triangle` class represents the triangle shape.
- The colors are predefined in the `Color` array in the JavaScript section.

### JavaScript Functionality

1. **Color Change**
   - When the "Change Color" button is clicked, the `Changecolor` event listener is triggered.
   - The background color of the circle element (`circle`) is changed to the color at the current index in the `Color` array.
   - The index is incremented, and if it reaches the end of the array, it wraps back to the beginning.

2. **Shape Change**
   - When the "Change Shape" button is clicked, the `changeShape` event listener is triggered.
   - Initially, the circle has the `.shape` class which defines its square shape.
   - Clicking the button toggles between adding the `.triangle` class to create a triangle shape and removing it to revert to the square shape.
   - The triangle shape is achieved through CSS border properties.

## Instructions

1. Open the HTML file in a web browser.
2. The circle will be displayed with its initial color and shape.
3. Click the "Change Color" button to cycle through different colors for the circle's background.
4. Click the "Change Shape" button to toggle between a square and a triangle shape.

Feel free to explore and modify the code to learn more about HTML, CSS, and JavaScript interactions.

## Author

My name is PANKAJ SAHU i am the owner of this repository. It is My geekster's m6 Day9 Class Challenge Project.

If you have any questions, suggestions, or feedback, you can reach out to the project maintainer:

 Name : [PANKAJ SAHU](https://linkedin.com/in/22pankajsahu-) <br>
 Email: [22pankajsahu@gmail.com](mailto:22pankajsahu@gmail.com)


---

This README provides a brief overview of the code's functionality and how to use it. Make sure to replace `[Date of Creation/Modification]` with the actual date when the code was created or last modified.
