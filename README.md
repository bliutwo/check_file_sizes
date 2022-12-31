# Check Size of Files and Directories

This script allows you to check the size of your files and directories.

## Update Fri Dec 30 2022

The command I found that works the best is this:

```
du -bsh * | sort -h
```

[Source](https://stackoverflow.com/questions/11720079/linux-command-to-get-size-of-files-and-directories-present-in-a-particular-folde)

## Usage

Run this script in a folder whose files you want to check.

```bash
$ bash check_file_sizes.sh
```

This does the same thing as the following command:

```bash
$ sudo du -sh * | sort -h
```
