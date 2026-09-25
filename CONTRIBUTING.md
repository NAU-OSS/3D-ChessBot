# Contributing
Contributions are welcomed and encouraged! If you want to contribute, feel free to fork the repository and create your own branch.
Pull requests will receive a response within 2 weeks of submitting.

### Pull Request Instructions
1. Fork the repository.
2. Create a new branch.
    ```git checkout -b feature/my-new-feature```
3. Make your changes.
4. Commit your changes.
    ```git commit -m "Add my new feature"```
5. Push the branch.
    ```git push origin feature/my-new-feature```
6. Open a pull request on GitHub.

# Style Guidelines
All code that is submitted should be properly indented and reasonably commented. Newcomers to the project should be able to easily understand the purpose of any additions you make.

### AI Policy
AI-assisted code is allowed so long as it is declared in the commit message and again in the pull request. 
For example: 
```
git commit -m "cleaned up the isValidMove function with the help of Claude"
```

Fully AI-generated code must be bracketed by comments specifying it. 
For example:
```
#Claude code start
    code...
#Claude code end
```

# Testing Requirements
There are no formal tests for the code in this repository. Simply run the code on your own device with the changes you've made and document any inconsistencies you encounter.
Formal tests will be introduced as a later stretch-goal.

# Documentation Standards
All commits should have detailed messages attached stating exactly what was changed and why.
