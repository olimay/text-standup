# text-standup

Command-line scripts to print out prompts for standups and different types of reviews.

Currently supports a basic daily text-based standup, and
more specific prompts for [Ultraworking Work Cycles][work-cycles].

Example usage: `python standup.py`

This will print the prompt to stdout in the terminal.

If you are on macOS, you can copy the prompt to the system clipboard by piping to the `pbcopy` command.

Example: `python standup.py | pbcopy`

[work-cycles]: https://www.ultraworking.com/cycles
