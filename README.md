# Project Title: streaming-01-getting-started

## Project Description
Working with streaming data also called data in motion is different than working with data at rest, for example, records in a database or rows in a file. While data at rest may be stored in a data warehouse, data lake, SQL database, NoSQL data store, graph database, log files, and other static sources, streaming data is unbound - typically generated in real time and/or triggered by events.   Often data in motion is processed in real time (or near real time) to allow analysts to generate information and make decisions based on continually generated, unbound data streams.
In this module we investigate what streaming data is and why it is important, discuss different sources of streaming data, and begin to prepare our development environments for working with real time data.

## Prerequisites

1. Python 3.10 or higher
1. VS Code
1. VS Code Extension: Python
1. Git (configured)


## Verify Installations / Update Default Python

In VS Code, open a terminal window (View / Terminal).
If macOS/Linux, change `python` to `python3` in the commands below.

```shell
git --version
python --version
python -m pip install --upgrade pip wheel
```

## Execute Utility Script (Diagnostics)
```shell
python util_about.py
```

## Additional Resources

1. For more information about Git in VS Code, see [Using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview).
1. For more information about editing Markdown in VS Code, see [Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown).
