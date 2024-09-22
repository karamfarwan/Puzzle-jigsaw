# Puzzle Jigsaw Without Hint

This project implements a classic jigsaw puzzle game where the user is required to assemble shuffled puzzle pieces to form a complete image. The goal is to accurately reconstruct the image without any hints or external help.

## Project Structure

- **Puzzle Generation:** The input image is divided into multiple puzzle pieces.
- **User Interface:** Allows players to drag and drop the puzzle pieces into the correct positions.
- **Completion Check:** Verifies when the user has correctly assembled the puzzle.

## Requirements

To run this notebook, you will need the following Python libraries:

- `pygame` (for game interface and handling events)
- `numpy` (for image processing)
- `opencv-python` (for reading and manipulating images)
- `matplotlib` (optional, for image visualization)

You can install the necessary libraries by running:

```bash
pip install pygame numpy opencv-python matplotlib
```

## Setup Instructions

1. Clone or download the repository.
2. Install the required dependencies as mentioned above.
3. Open the Jupyter notebook `Puzzle_Jigsaw_without_hint.ipynb`.
4. Run the notebook to start the puzzle game.

## How to Play

1. **Loading the Puzzle:** The game loads an image that is split into several puzzle pieces.
2. **Solving the Puzzle:** The puzzle pieces are shuffled, and the user must drag and drop them into their correct locations.
3. **Completion:** Once all the pieces are correctly placed, the game verifies the completion and displays a success message.

## Methodology

- **Image Segmentation:** The input image is split into a grid of smaller pieces, which are shuffled randomly.
- **User Interaction:** Players can interact with the pieces using the mouse to drag and place them.
- **Puzzle Validation:** The game checks whether all pieces are placed in their correct positions to determine completion.

## Usage

1. Run the notebook to start the game.
2. Use the mouse to drag puzzle pieces into place.
3. Continue rearranging until the image is correctly assembled.

## License

This project is open-source and available under the MIT License.

