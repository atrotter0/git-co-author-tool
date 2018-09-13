# Git Co-Author Tool

#### By Abel Trotter, 09.13.2018

## Description

A CLI tool for setting co-author config and creating co-author git commits, ensuring that Epicodus students recieve full credit for their git commits throughout the pairing process.

## Setup

1. Add `git-go-author-tool.sh` to your project .gitignore file
1. Clone the repo
1. Navigate into the clone directory
1. Copy the `git-go-author-tool.sh` file into your project
1. Run `chmod 777 ./git-go-author-tool.sh`
1. Run `./git-go-author-tool.sh`
1. Enter `1` to set co-author configuration
1. Enter `2` to create commit message
1. Enter `3` to push commit to master

## Usage

This script will need to be running in a seperate tab while you are working on your project. I suggest using `git add` from one tab, and switch back to the tab where this script is running to make your co-author commits.

**Key Features:**

### Set co-author config
This must be set each time you run this tool. If you cntrl-c and quit this tool, you will need to once again set your co-author config the next time you run the script.

### Create commit
This will accept a string as your commit message, and append the co-author tags based on the configuration from Main Menu option 1. You should use `git add` from another tab, and switch back to the terminal tab where this script is running in order create commit (option 2), and optionally push to master (option 3).
  
### Push to master
This will run the command `git push origin master`. Only use it if you have an `origin` reference.

## Contribution Requirements

1. Clone the repo
1. Make a new branch
1. Commit and push your changes
1. Create a PR

## Technologies Used

* Bash
* Git

## Links

* [Github Repo] ()

## License

This software is licensed under the MIT license.

Copyright (c) 2018 **Abel Trotter**