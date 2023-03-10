# logprog
Simple script that shows progress of a operation extracted from a log file.

## Example
```
> logprog path/to/a/file
```
output:
```
11.37% ETA: 11:04:43
```
(the output is changing over time)

To exit the script press `Ctrl+C`

## Features
- set how often it updates
- set the amount of last lines from the file to read for each output
- set the pattern to match the percentage
