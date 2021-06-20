# Bash Scripts

Some of the functions that I wrote to automate some of the process that I use often in my workflow.

 - [How to use](#how_to_use)

## How to use

1. You can download the files or copy them to your linux system. To clone write in terminal

	```bash
    	git clone 
	```
2. You can either clone the folder inside a folder which is already in the `PATH` or add the folder into the `PATH`.
	To see which folders are in the `PATH` type

	```bash
		echo $PATH
	```
	And to add the new folder in the `PATH` type

	```bash
		export PATH=path/to/file:$PATH
	```

3. **NOTE**: I use `zsh` instead of `bash` so if you use `bash` you need to change the first line of each file from `#!/usr/bin/zsh` to `#!/bin/bash`. Or for other shell `*sh` (e.g. `fish`, `csh` etc.) type
	```bash
		which *sh
	```
	and use the output from that to replace `/usr/bin/zsh`.



## Files

 - [`makeslide`](#makeslide)
 - [`makeslide1`](#makeslide1)
 - [`createslide`](#createslide)
 - [`formathtml`](#formathtml)
 - [`mdview`](#mdview)
 - [`nbview`](#nbview)
 - [`smartcopy`](#smartcopy)

### `makeslide` and `makeslide1`

It creates a reveal.js slideshow(a html file) from markdown file(s).

### `mdview`

### `nbview`

### `formathtml`

