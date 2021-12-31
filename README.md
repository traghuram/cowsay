# Homework 1: command-line interface

In your home directory, make a folder called `Development`, if it doesn't exist. This is where we will keep all of the code for the class. Next, make sure that you are inside that folder, by checking the output of the following command:

```shell
pwd
```

If `pwd` shows that you are in a different directory, run `cd ~/Development` and check with `pwd` again.

## How to clone this repo

Next, clone this repository by clicking the green button in the upper right corner, selecting `SSH` and copying the string that looks like `git@github.com:code4policy/<REPO-NAME>.git` (`<REPO-NAME>` will be the name of your repository). Then, in the terminal run the following:

```
git clone git@github.com:code4policy/<REPO-NAME>.git
```

Note that by default, git will clone the repository into a folder with name `<REPO-NAME>`. After the repo is cloned, open that directory (use `cd`).


## Installation of `cowsay`

1. Install the `cowsay` command

    - Mac: `brew install cowsay`
    - Ubuntu: `sudo apt-get install cowsay`

2. Run the following command in the terminal:

    ```shell
    /bin/bash cow.sh
    ```

    Examine the output and the script that generated it (`cow.sh`).

3. Edit scripts named `task_X.sh`, where `X` is the number of the task in the list below, so that they produce the desired output (see comments inside each file). When you push the updated script, it will be graded automatically. If there is any error, inspect the error, and commit again. The expected output is in `expected_answers.txt`. Run `man cowsay` for documentation.

### Tasks
(each phrase, including bonuses, is worth 10 points):

1. Make cow say: 1) Individuals and interactions over processes and tools 2) Working software over comprehensive documentation 3) Customer collaboration over contract negotiation 4) Responding to change over following a plan

2. Make a dead cow say the same text

3. Make cow say "moo" with eyes changed to "zz"

4. Make cow say "moo" with tongue changed to "$$". (hint: is it not displaying properly? google "escaping characters in bash")

5. Make cow say "moo" with eyes changed to "zz" AND tongue changed to "$$"

6. Make cow think "ask what you can do!" with thought bubble wrapping every 4 characters

7. (bonus task) Turn cow into a moose that says "Hello, world!"

8. (bonus task) Turn cow into a fox that says "Hello, world!" (hint: You'll have to install a new cow - https://raw.githubusercontent.com/paulkaefer/cowsay-files/master/cows/fox.cow)
