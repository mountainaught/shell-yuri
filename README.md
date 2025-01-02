no #### you you don't get a nice intro readme install this on your bash you'll be happy probably idk.
### btw this is a work in progress i need to go on dynasty reader and grab some lines for you fine people

original credit to: sudofox/shell-mommy

<img src="preview.png" alt="Example" ></a>

## Installation

put the yuri bash code in a local bin folder, add that folder to your PATH, then force bash into calling yuri every single time you want to run the simplest command. isn't this fun?

```
export PROMPT_COMMAND="mommy \\$\\(exit \$?\\); $PROMPT_COMMAND"
```

## Usage

To use the `mommy` function, simply pass a command as an argument and `mommy` will provide a supportive response based on the exit status of the command. Depending on the exit status, `mommy` will provide a response of praise or encouragement.

```sh
mommy ls
# Output: Good girl! mommy's so proud of you! ❤️

mommy this-command-does-not-exist
# Output: Just a little further, sweetie~ ❤️
```

## Example

```
# Set custom affectionate term and pronouns
export SHELL_MOMMYS_LITTLE="kiddo"
export SHELL_MOMMYS_PRONOUNS="them"

# Use the mommy function to run a command
mommy ls

# Output:
# That's a good kiddo~ ❤️
```
