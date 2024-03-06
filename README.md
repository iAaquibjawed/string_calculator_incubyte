# String Calculator in Ruby

This repository contains a simple implementation of a string calculator in Ruby, developed as part of a Test-Driven Development (TDD) exercise.

## Task Description

The task was to create a string calculator with the following functionalities:

- **Basic Addition**: Handles empty string, single number, and multiple comma-separated numbers input, returning their sum.
- **Newline Separator**: Supports newline characters ('\n') as separators in addition to commas.
- **Custom Delimiters**: Allows custom delimiters specified at the beginning of the string.
- **Negative Number Handling**: Throws an exception for negative numbers with a message indicating which negative numbers were encountered.

## Usage

To use the string calculator, include the `string_calculator.rb` file in your Ruby project. Call the `StringCalculator.add` method with the desired input string to calculate the sum.

## Testing

Unit tests are provided in the `test_string_calculator.rb` file. To run the tests, execute the following command:

```bash
ruby test_string_calculator.rb
