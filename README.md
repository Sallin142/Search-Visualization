
# Vacuum Search

## Overview
Vacuum Search is a Python application developed to simulate a vacuum cleaner agent that searches and cleans a grid environment. The application supports various search algorithms including BFS, DFS, UCS, Greedy, and A*. This project demonstrates the implementation of these algorithms and their application in an artificial intelligence context.

## Project Status
**Note**: The application is currently functional and can be used to simulate different search algorithms in a static, fully observable grid environment.

## Features
- **Search Algorithms**: Implementation of BFS, DFS, UCS, Greedy, and A* search algorithms.
- **Grid Environment**: Simulation of a 2D grid environment with dirty and blocked rooms.
- **Heuristic Functions**: Support for various heuristics like Manhattan and Euclidean distances.
- **Cost Functions**: Incorporation of additional costs for turns and grid positioning.

## Technologies Used
### Backend:
- Python

### Tools:
- GitHub
- Python unittest

## Repository Structure
The project is organized into the following main directories and files:

### Main Directory
- `vacuum_search.py`: Main script to run the search algorithms.
- `README.md`: Project documentation.
- `requirements.txt`: Python dependencies.
- `.gitignore`: Specifies files to be ignored by Git.

### Other Files and Directories
- `agents.py`: Contains the agent classes and their behaviors.
- `search.py`: Implementation of various search algorithms.
- `utils.py`: Utility functions and classes.
- `__pycache__/`: Cache directory for compiled Python files.
- `.idea/`: Directory for project-specific settings and configurations for an IDE.

## Installation
Clone the repository:

\`\`\`bash
git clone https://github.com/Sallin142/vacuum-search.git
cd vacuum-search
\`\`\`

Install dependencies:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

## Usage
To run the application with the Greedy search algorithm:

\`\`\`bash
python vacuum_search.py -s Greedy -n -a
\`\`\`

### Setup
To set up the application locally, follow these steps:

1. **Environment Variables**: Create a `.env` file in the root directory and populate it with the necessary environment variables. Refer to `.env.example` for required variables.
2. **Configuration**: Ensure the environment is properly set up with the necessary configurations.

## Known Issues
- The application currently does not support persistent storage of the grid environment state.

## Future Improvements
- **Refactoring**: Plan to update deprecated libraries and improve the codebase.
- **New Features**: Potential to add more features like dynamic environment changes, real-time visualization, etc.
- **Testing**: Implement comprehensive unit and integration tests.

## Contributors
- Sallin Koutev - [GitHub](https://github.com/Sallin142)

## Contact
For any questions or feedback, please contact me at ska287@sfu.ca.


## Languages
- Python
