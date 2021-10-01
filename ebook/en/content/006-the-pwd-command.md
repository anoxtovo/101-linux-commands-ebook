# The `pwd` command

The `pwd` command prints the current working directory.  
  
Example:

```
pwd
```

Syntax: 

```
pwd [OPTION] 
```
  

### Logical:

Use the `-L` option after the pwd command.

Syntax:
```
pwd -L
```

### Physical:

if environment includes symlinks, use pwd with -P

Syntax:
```
pwd -P
```

avoid all symlinks