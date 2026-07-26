# Calculator App

A simple, elegant calculator application built with vanilla JavaScript, HTML, and CSS.

## Project Description

This is a functional web-based calculator that allows users to perform basic arithmetic operations. The project demonstrates fundamental web development concepts including HTML form handling, inline JavaScript event handlers, and CSS styling with modern design techniques.

## Features

- **Basic Arithmetic Operations**: Addition (+), Subtraction (-), Multiplication (*), and Division (/)
- **Clear Function (AC)**: Clear the display to start a new calculation
- **Delete Function (DEL)**: Remove the last entered digit
- **Decimal Support**: Add decimal points for floating-point calculations
- **Double Zero (00)**: Quick input for entering multiple zeros
- **Responsive Buttons**: All buttons are interactive with hover effects
- **Real-time Display**: Shows the current input and calculation results

## File Structure

```
calculator project 2/
├── index.html     # HTML structure and calculator layout
├── style.css      # CSS styling and design
├── script.js      # External JavaScript file (currently empty)
└── README.md      # Project documentation
```

## How to Use

1. Open `index.html` in your web browser
2. Click number buttons to enter values
3. Click operator buttons (+, -, *, /) to select an operation
4. Click the equals button (=) to calculate the result
5. Use AC to clear the display completely
6. Use DEL to remove the last digit
7. Use the decimal point (.) for decimal numbers

## Technology Stack

- **HTML5**: Semantic markup and form elements
- **CSS3**: Modern styling with flexbox layout, shadows, and gradients
- **JavaScript (Vanilla)**: Inline event handlers for button operations and the `eval()` function for calculation

## Design Highlights

- **Color Scheme**: Dark gray calculator with cyan accent colors for operators
- **Layout**: Centered design with a light blue background
- **UI/UX**: Neumorphic shadow effects on buttons for a modern, tactile appearance
- **Responsive**: Uses flexbox for proper alignment and spacing

## Key Implementation Details

- **Button Grid**: Organized in 4 rows of number buttons plus operation buttons
- **Display Input**: Full-width input field showing current calculation
- **Inline JavaScript**: Each button uses `onclick` attributes to handle user input
- **String Manipulation**: Uses `displayNums.value` to manage the display content
- **Calculation**: Uses JavaScript's `eval()` function to compute results

## Future Enhancements

- Add keyboard support for number and operation input
- Implement calculator history/memory functions
- Add more advanced operations (square root, percentage, etc.)
- Move event handlers from HTML to external JavaScript file
- Add error handling for invalid expressions
- Implement undo/redo functionality

## Browser Compatibility

Works in all modern browsers that support:
- HTML5
- CSS3 (flexbox, box-shadow, border-radius)
- JavaScript ES6+

## Notes

- The calculator currently uses `eval()` for calculations, which works but is generally discouraged in production applications for security reasons
- Consider migrating event handlers to external JavaScript for better code organization and maintainability
