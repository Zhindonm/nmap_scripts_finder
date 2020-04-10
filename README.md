# nmap_scripts_finder
Bash program to find NMAP scripts by categories in `/usr/share/nmap/scripts/`.

This is particularly useful if you only want to use scripts that are `safe`, or any other category, but don't know which ones are those.

## Usage

Find scripts of category `foo`:  
```
$ ./nmap_scripts_finder foo
Available NMAP scripts in /usr/share/nmap/scripts/'
Category : foo

...
```

To list available scripts' categories simply run the program without any arguments:  
```
$ ./nmap_scripts_finder
Enter a category to search for NMAP scripts
Available categories:

"auth"
"broadcast"
"brute"
...
```

## Installation

1. `git clone https://github.com/Zhindonm/nmap_scripts_finder.git`
2. `chmod +x nmap_scripts_finder`


