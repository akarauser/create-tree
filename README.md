# create-tree
Project Directory Visualizer

This script generates a visual directory tree for a given project path, excluding ignored files (e.g., .venv, .git, .env). It provides a clean, recursive output using ASCII symbols for readability. The code follows best practices like type hints, recursive generator design, and efficient path filtering while avoiding unnecessary computations. It leverages pathlib for cross-platform compatibility and yields lines dynamically for memory efficiency. A key technique is the dynamic prefixing system (TEE, ELBOW, PIPE) to visually distinguish directory branches, improving clarity.
