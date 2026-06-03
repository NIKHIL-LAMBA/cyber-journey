# Linux Fundamentals Part 1

## pwd
Purpose: Shows the current working directory.

Example:
```bash
pwd
```

## ls
Purpose: Lists files and directories.

Example:
```bash
ls
```

## cd
Purpose: Changes directory.

Example:
```bash
cd Desktop
```

## whoami
Purpose: Shows the current logged-in user.

Example:
```bash
whoami
```

## echo
Purpose: Prints text to the terminal.

Example:
```bash
echo Hello
```

## find
Purpose: Searches for files and directories.

Example:
```bash
find / -name access.log
```

## grep
Purpose: Searches for specific text inside files.

Example:
```bash
grep "error" access.log
```

## grep -r
Purpose: Recursively searches through directories.

Example:
```bash
grep -r "password" .
```

## *
Purpose: Wildcard that matches multiple files.

Example:
```bash
ls *.txt
```

## >
Purpose: Redirects output and overwrites a file.

Example:
```bash
echo Hello > file.txt
```

## >>
Purpose: Appends output to a file.

Example:
```bash
echo World >> file.txt
```

## &
Purpose: Runs a process in the background.

Example:
```bash
firefox &
```

## &&
Purpose: Runs the second command only if the first succeeds.

Example:
```bash
mkdir test && cd test
```

## access.log
Purpose: Common web server log file used for analysis.

Example:
```bash
cat access.log
```
