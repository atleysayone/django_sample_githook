## How to setup project for development

# What is githook
- Git hooks are scripts that run automatically every time a particular event occurs in a Git repository.
- Hooks are local to any given Git repository


# Install pre-commit pep8 checker using githook:
- Githooks are not getting versioned same are other files(resided ./git/hooks)
- Add hooks inside hooks dir inside project
- After pull use command “ln -s ../../hooks/pre-commit .git/hooks/”
- pep8 should be installed  in the system level
- pip install pycodestyle

# Output
- ![alt text](https://image.ibb.co/gnOgzd/Screenshot_from_2018_06_12_16_02_40.png)