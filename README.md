# Valgrind suppression extractor
Steps:
- get the stdio from the make check step of valgrind builder and place it in root
- run all cells from main.ipynb
- use the suppressions files that is generated in the root directory to run valgrind again