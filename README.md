# C_normChecker
A simple Python script to check the Epitech C coding style.

[Epitech C coding style document](epitech_c_coding_style.pdf)

## Usage
```
$ ./CnormChecker --help

DEFAULT BEHAVIOR:
	Check every files in the current folder recursively

USAGE:
	 ./CnormChecker [OPTIONS] [FILES / FOLDERS]

OPTIONS:
	-h,--help
		Print this help message.
	-v,--version
		Show version information.
	-s,--silent
		Enable silent mode.
	-c,--nocolor
		Enable nocolor output mode.
	-D,--debug
		Add some debug output.
	-R,--recursive
		Enable recursive mode.

ARGS:
	<FILE>
		File(s) to check.
	<FOLDER>
		Folder(s) that every files inside will be check.
```

## Color code
- ![#f03c15](https://placehold.it/15/f03c15/000000?text=+)  Major mistake
- ![#c5f015](https://placehold.it/15/c5f015/000000?text=+)  Minor mistake
- ![#1589F0](https://placehold.it/15/1589F0/000000?text=+)  Info

## Checks

### In sources files
- [x] Header
- [x] Functions separations
- [ ] Pre-processor directives indentation
- [ ] Global variables
- [ ] Static keyword
- [ ] Functions name
- [x] Number of columns
- [x] Number of lines inside a function
- [ ] Arguments of the functions
- [x] Comment inside a function
- [ ] Line code content
- [x] Indentation
- [ ] Spaces
- [ ] Curly brackets
- [ ] Variable declaration
- [ ] Line jumps
- [ ] Naming identifiers
- [ ] Structures
- [ ] Pointers
- [ ] Conditional branching
- [ ] Ternary
- [ ] Goto
- [ ] Constant pointers
- [ ] Header files content
- [ ] Include guard in header files
- [ ] Macros

### Others
- [x] Content of the delivery folder
- [x] Files and folders names
