# Contributing
If you are interested in contributing to this project, we welcome any and all developers who are interested! And don't worry, you don't have to do anything very technical or complicated to contribute to this project. Anyone of any skill level is welcome to propose changes.
There are two methods to contribute to this project: Through pull requests (PRs) and through our Issue tracker. The next two sections will outline how to contribute to each and what qualifies for each type.

## Pull Requests
Pull requests are used to commit changes to the main branch of the project. Use pull requests if you have a direct change to the code. Here is the process for making a change and creating a PR:
1. Create a clone of the repository on your local machine: ``` git clone https://github.com/NAU-OSS/ModelPrimer.git ```
3. Make sure to create a separate branch for your changes: ``` git checkout -b [branch_name] ```
4. Make your changes to the code
5. Add your changes by adding the files you updated: ``` git add [file] ```
6. Commit your changes: ``` git commit -m "Commit msg" ```
7. Push changes back to the main repository: ``` git push origin [branch_name] ```
8. Go back to the website and create a pull request. Don't forget to include a description of your changes!
After your pull request has been submitted, it will be subject to a code review, where another 2 developers must approve your code before it gets pushed to the main branch.

## Issue tracker
The issue tracker in this project is used to report bugs, propose new features, or propose any general project changes. If you want to add any of these to the issue tracker, make sure that you add the appropriate tag to your issue so that they can be categorized properly (i.e. use the "bug" tag for a bug).

## Formatting
Code must be formatted with these guidelines to keep the project consistent and easily readable for the next contributor. Remember, you aren't the only one looking at this code!
1. All variables must be self-documenting, no use of single-letter variables
2. Indenting will be done with 4 spaces instead of a single tab
3. Precompiled variables and macros will be named all uppercase with underscores
4. Constants and global variables will be named all lowercase with underscores
5. All other functions and local variables will be named with camel case (i.e. functionName)
6. Code must be well commented within reason

## Testing
All functions that are unit-test applicable must have at least 3 tests each. If your function is not testable through unit testing, you must include at least one test if possible. The test files for your functions can be included in the same file path as your file, under the "Tests" directory.

## Community Expectations
While this project is open-source and we encourage any manner of contribution, we still expect a high level of quality for this project. Any changes proposed for this project should be put to high standards and be subject to review and possibly denial if it does not meet the project's standards.
