# Karolina's Crash Course

    2020 Ondrej Sika <ondrej@ondrejsika.com>
    https://github.com/ondrejsika/karolina-crash-course

## Agenda

- [Bash](#bash)
- Python
- SQL
- ElasticSearch

## Bash

### Basic Commands

- `pwd` - print working directory
- `mkdir <dir>` -
- `ls` - list directory
- `cd <dir>` - change directory
- `cat <file>` - print out file
- `touch <file>` - create new blank file
- `cp <from> <to>` - copy
- `mv <from> <to>` - move
- `echo <text>` - text
- `tree` - show directory structure tree

```
pwd
mkdir -p tmp/foo
cd tmp/foo
touch a b
echo hello > c
ls
ls -al
mkdir x
mv a b x
ls
ls x
cp c x/bar
ls
ls x
cat c
cat x/bar
rm c
rm x
rm -rf x
```

### Terminal Shortcuts

#### Control + W

Using this keyboard combination will delete the word immediately before, or to the left of, the cursor.

#### Control + R

If you need to locate a previously used command in Terminal, use Control and R. It will open up [(reverse-i-search)`':] and allow you to find a previously used commands that you may need to access again.

#### Control + A

Using Command and A will take you to the end, or the far right, of the line where your cursor is.

#### Control + E

This shortcut is the opposite of Command and A. Command and E will take you back to the beginning, or the far left, of the line you are currently working on.

#### Control + C

If you need to kill what's currently running, us Control and C in Terminal to abort the current application.

#### Control + U

This shortcut clears the entirety of the line before the cursor. So, if you get to the end of a line and realize the whole thing is wrong, use Control and U to delete it all.

#### Control + K

Using Control and K will have the opposite effect as using Control and U. This will clear the line that appears after the cursor. It is helpful if you need to change or delete the latter half of a line.

#### Control + L

This will clear the entire Terminal screen you're working on, deleting everything.

#### Control + D

This will cause you to exit the current shell in Terminal.

#### Control + B

This shortcut moves the cursor back to the previous character on the line. It gives you the same result as using the left arrow key, but keeps you on the home row keys.

## Resources

- https://www.techrepublic.com/article/20-terminal-shortcuts-developers-need-to-know/
