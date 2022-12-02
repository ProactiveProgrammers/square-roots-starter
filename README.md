# Square Roots

After cloning this repository to your computer, please take the following steps:

- Follow the instructions on the Proactive Programmers web site for this project
- Use the `cd` command to change into the directory for this repository
- Change into the program directory by typing `cd squareroot`
- Install the dependencies for the project by typing `poetry install`
- Run the program in with both algorithms by typing:
  - `poetry run squareroot --number 25 --approach exhaustive`
  - `poetry run squareroot --number 25 --approach exhaustive --profile`
  - Please note that the program will not work unless you add the required source code
  - Please refer to the `writing/reflection.md` file for all of the ways to run the program
- Confirm that the program is producing the expected output
- Make sure that you frequently commit to your GitHub repository
- As you commit to your repository, you should always use descriptive commit messages
- Use a `docker run` command for your operating system to run GatorGrader
- Please note that:
  - Performance profiling with `pyinstrument` in a Docker container may not work as expected
  - Running `poetry install` in both the Docker container and your laptop may not work as expected
- Provide all of the required responses in the `writing/reflection.md` file
- For more details about this project, please visit: https://proactiveprogrammers.com/data-abstraction/programming-projects/square-root/
