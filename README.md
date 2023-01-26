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
simply stay in Alfred and ask:

    $ howdoi properly use tar command
    > tar -czf /tmp/workspace.tar.gz .

## Installation

Make sure howdoi is installed on your machine with `brew install howdoi`.

## Usage

Invoke the Alfred workflow with the keyword Question Keyword (default: `howdoi`) and then your query. The output will be shown as large type and also copied to the clipboard. Use ⌘↩ to open the answer's web page instead.

![Typing the howdoi query](images/howdoi-alfred-window.png)

New to howdoi? You can get started by running:

    howdoi howdoi

## Notes

If `howdoi` is installed to a non-standard Homebrew location (or with `pip`) then you need to tell Alfred about your appropriate `PATH`.

  - Open the Workflow in Alfred
  - Click "prepare workflow configuration" in the top right (the icon looks like `(x)`)
  - Select the "Environment Variables" tab
  - Make a new entry with name `PATH` and value as the text output of entering `echo $PATH` in a terminal (e.g. `/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Users/username/.homebrew/bin`)

## Useful Links

- [howdoi](https://github.com/gleitz/howdoi/) github page
