<p align="center">
    <a href="https://pypi.python.org/pypi/howdoi">
        <img src="https://www.dropbox.com/s/dk13iy2uoufdwr7/HowDoIcolor512.png?raw=1" alt="Sherlock, your neighborhood command-line sloth sleuth" />
    </a>
</p>

# howdoi

## Instant coding answers via Alfred

⚡ Never open your browser to look for help again ⚡

## Introduction to howdoi

Are you a hack programmer? Do you find yourself constantly Googling for
how to do basic programming tasks?

Suppose you want to know how to format a date in bash. Why open your
browser and read through blogs (risking major distraction) when you can
simply stay in the console and ask howdoi:

    $ howdoi properly use tar command
    > tar -czf /tmp/workspace.tar.gz .

## Installation

- Make sure howdoi is installed on your machine with `pip install howdoi`.
- Make sure the Alfred extension knows the path to the executable (otherwise you will get the error `/bin/bash: howdoi: command not found`).
- Open Alfred, navigate to Workflows, select Howdoi, and then click "Configure Workflow".
- Open the terminal, run `which howdoi`, and paste the output into the User Configuration variable called `Howdoi path`.

## Usage

Invoke the Alfred extension with the keyword `howdoi` and then your query.

<p align="center">
    <img src="https://www.dropbox.com/s/dkcqzd2qoppvsn2/howdoi-alfred-window.png?raw=1" alt="Typing the howdoi query" />
</p>

The output will be shown as a notification and also copied to the clipboard.

<p align="center">
    <img src="https://www.dropbox.com/s/l3opn1on1ak07ty/howdoi-notification.png?raw=1" alt="Receiving a notification of the howdoi response" />
</p>

New to howdoi? You can get started by running:

    howdoi howdoi

## Useful Links

- [howdoi](https://github.com/gleitz/howdoi/) github page
