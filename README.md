# Hair Growth Calculator

A simple GUI application to calculate potential hair growth over a specified period using Python's Tkinter library.

## Features

- Input your current hair length in centimeters.
- Specify the number of years over which your hair will grow.
- Calculate the expected hair length based on a predefined growth rate.
- User-friendly interface for easy data entry.

## Requirements

- Python 3.x
- Tkinter (comes pre-installed with Python)

## Installation

1. Clone the repository or download the source code.
2. Make sure you have Python 3.x installed on your machine.
3. Run the script using the command:

   ```bash
   python hair_growth_calculator.py
   ```

## Usage

1. Enter your current hair length in the first input field.
2. Enter the number of years you wish to calculate hair growth for.
3. Click the "Calculate" button to view the expected hair length.

## Example

- **Current Hair Length**: `30` cm
- **Years**: `5`
- **Expected Result**: `105 cm` (assuming an average growth rate of 15 cm/year).

## Code Overview

The core function of the application is `hair_calc`, which:

- Retrieves user input for hair length and years.
- Calculates the total hair length based on a predefined growth rate (15 cm/year).
- Displays the result in the GUI.

## Error Handling

The application includes basic error handling to ensure users enter valid numeric inputs. If invalid input is detected, an error message will be displayed.

## License

This project is open-source and available under the MIT License.

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for any suggestions or improvements.

## Acknowledgements

- Thanks to the Python and Tkinter communities for providing resources and documentation.
