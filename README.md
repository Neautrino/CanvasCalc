# CanvasCalc

CanvasCalc is an interactive web application that combines the power of freehand drawing with mathematical expression recognition and LaTeX rendering. Draw your equations on a digital canvas and watch as they come to life in beautifully typeset LaTeX format.

## Features

- **Interactive Canvas**: Draw mathematical expressions freehand
- **Expression Recognition**: Automatically interprets drawn symbols and equations
- **LaTeX Rendering**: Converts recognized expressions into high-quality LaTeX format
- **Draggable Results**: Easily reposition rendered LaTeX expressions on the canvas
- **Color Selection**: Choose from a variety of colors for drawing
- **Real-time Calculation**: Evaluate expressions and display results instantly
- **Responsive Design**: Works seamlessly on various device sizes

## Technologies Used

- React.js
- TypeScript
- MathJax
- Axios
- Mantine UI
- React-Draggable

## Getting Started

### Prerequisites

- Node.js (v14.0.0 or later)
- npm (v6.0.0 or later)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/canvascalc.git
   ```

2. Navigate to the project directory:
   ```
   cd canvascalc
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Create a `.env` file in the root directory and add your API URL:
   ```
   VITE_API_URL=your_api_url_here
   ```

5. Start the development server:
   ```
   npm run dev
   ```

6. Open your browser and visit `http://localhost:3000` (or the port specified in your console)

## Usage

1. Use the canvas to draw your mathematical expression
2. Select different colors using the color swatches
3. Click the "Calculate" button to process your drawing
4. View the LaTeX-rendered result, which appears as a draggable element on the canvas
5. Use the "Reset" button to clear the canvas and start over

## Contributing

We welcome contributions to CanvasCalc! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request

Please make sure to update tests as appropriate and adhere to the existing coding style.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Thanks to the MathJax team for their excellent LaTeX rendering library
- Inspired by the need for intuitive mathematical expression input in digital environments