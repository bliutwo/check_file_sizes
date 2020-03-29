# Check Size of Files and Directories

This script allows you to check the size of your files and directories.

## Usage

Run this script in a folder whose files you want to check.

```bash
$ bash check_file_sizes.sh
```

This does the same thing as the following command:

```bash
$ sudo du -sh * | sort -h
```

Alternatively, you could run this command:

```bash
$ du -h --max-depth=1 | sort -hr
```
