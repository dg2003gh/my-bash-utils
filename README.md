# My bash utilities

"My bash utils" is a collection of scripts that make some things I do every day a little easier.

### How to use (for beginners ;-;).

You can open your .bashrc which is in your home directory with your preferred editor, I'm using nvim:

```
nvim ~/.bashrc
```

After that, you can paste the following code however you want, I recommend it in the last line of the file:

```
# Personal configuration
export PATH=$PATH:~/Documents/my-bash-utils/bin
```

Open a new terminal or type the command `source ~/.bashrc` and test one of the commands listed below! Like this:

```
kbled -o
```

Below is a list of the scripts with their names, descriptions, last updated date, and bash version.

 |title|description|date|version|GNU bash| 
|-----|-----------|----|-------|--------|
 | gitfast | A command to add, commit, push to a git repository. | 01-04-2024 | 0.1.0 | 5.2.21|
| kbled | turn on your keyboard led on wayland with one command. | 01-04-2024 | 0.1.0 | 5.2.21|
| dkdroid | a command to easily run a android docker container.. | 12-26-2023 | 0.1.0 | 5.2.21|
| readme-updater | Updates a git repository README.md with file header information everytime a it is added. | 01-05-2024 | 1.1.0 | 5.2.21 |