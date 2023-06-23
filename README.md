# Mastermind Solver Using Knuth's Algorithm

This repository contains a Python script that uses Donald Knuth's Five-guess Algorithm to intelligently solve the classic game of Mastermind.

## Background

Mastermind is a code-breaking game where one player sets a secret code, and the other tries to guess it within a certain number of turns. The guesser receives feedback on the number of correct colors in the right and wrong positions.

Donald Knuth, in 1977, developed an algorithm that could guarantee a correct guess in five moves or fewer. This project showcases the power of simplicity and efficiency by implementing this algorithm.

For detailed information on Knuth's Algorithm, refer to [Donald Knuth's original article](http://www.cs.uni.edu/~wallingf/teaching/cs3530/resources/knuth-mastermind.pdf).

## How It Works

The script generates all possible combinations of colors, and then, iteratively, it guesses the secret code based on the feedback (black and white pegs). It uses Knuth's minimax approach, eliminating possibilities that don’t match the feedback until the secret code is guessed.

## Potential Use Cases

This project is not only a game solver but can also serve as an inspiration for solving real-world problems where options need to be intelligently guessed based on limited feedback.

## Contributing

Contributions are welcome. Please feel free to submit a pull request or create an issue.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Donald Knuth for his brilliant algorithm.
- Mastermind game creators, Mordecai Meirowitz.

