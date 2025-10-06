# Ubuntu VMware Installation Lab: Exercise Files

This repository contains a set of exercise files designed for hands-on practice with Ubuntu in a VMware environment. The files and folders are intended to help you learn and demonstrate skills in Linux file management, scripting, text processing, and system administration.

## Directory and File Overview

### Top-Level Files

- **dupes.txt**: Contains repeated lines of text. Use this file for exercises involving text deduplication, searching, or scripting.
- **poems.txt**: Includes classic poems ("Ozymandias" by Percy Shelley and "The Tyger" by William Blake). Useful for text manipulation, searching, or formatting tasks.
- **simple_data.txt**: Tab-separated values with names, IDs, and teams. Ideal for practicing data extraction, parsing, and scripting.
- **test.sh**: A simple Bash script that prints a colored message. Use this to test shell scripting and script execution.
- **log.tar.gz**: A compressed archive (binary file), likely containing log files. Use this for exercises involving file extraction, compression, or log analysis.

### Departments Directory

The `departments/` folder simulates a company directory structure with the following subfolders:

- **engineering/** (drawings/, invoices/, materials/)
- **finance/** (documents/, invoices/, spreadsheets/)
- **hr/** (candidates/, employee info/, policies/)
- **marketing/** (empty)
- **sales/** (affiliates/, enterprise/, presentations/, promotions/)

All subfolders are currently empty, allowing you to practice file creation, organization, permissions, and navigation.

## Suggested Lab Activities

1. **File and Directory Navigation**: Practice using `cd`, `ls`, `tree`, and other commands to explore the directory structure.
2. **Text Processing**: Use tools like `cat`, `grep`, `awk`, `sort`, and `uniq` on `dupes.txt`, `poems.txt`, and `simple_data.txt`.
3. **Shell Scripting**: Run and modify `test.sh` to learn about Bash scripting and terminal output formatting.
4. **Archive Management**: Extract and inspect `log.tar.gz` using `tar` and related commands.
5. **File Permissions and Organization**: Create, move, and set permissions on files within the `departments/` subfolders.

## Getting Started

1. Clone or copy this repository into your Ubuntu VM.
2. Open a terminal and navigate to the project directory.
3. Use the provided files and folders to complete your lab exercises as instructed.

## Downloading Exercise Files from GitHub (Ubuntu)

To download the zipped exercise files from GitHub, unzip them, and move the folder to your `Documents` directory, use the following commands in your Ubuntu terminal:

```bash
# Download the zipped file
wget https://github.com/kwameassa/Exercise-Files/archive/refs/heads/main.zip

# Unzip the file
unzip main.zip

# Move the extracted folder to your Documents directory
mv Exercise-Files-main ~/Documents/
```

This will place the `Exercise-Files-main` folder inside your `Documents` directory for easy access.

---
These files are intended for educational use in Ubuntu/VMware labs. Feel free to modify or extend them for your own practice.
