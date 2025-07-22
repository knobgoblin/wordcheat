# wordcheat

A simple utility to aid cheating on crosswords and other word puzzles.  Written in Python with no particular finesse involved.

## Installation

1. Copy the executable to somewhere in your path.
1. Make the executable, um, executable.

### Example

Assuming that ```/usr/local/bin``` is in your path and you have write access to it.

```bash
cp /path/to/this/repository/wordcheat /usr/local/bin
chmod 0755 /usr/local/bin/wordcheat
```

## Usage
### To match words

Pass the word as a parameter and substitute any missing letters with a period ('.').

```bash
wordcheat c.lo.t..y
```

This should return ```colostomy```.

### To find anagrams

Just pass the word as a parameter.

```bash
wordcheat tame
```

This should return:

```
mate
meat
meta
tame
team
```
