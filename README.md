# nmap_scripts_finder
Bash program to find NMAP scripts by categories in `/usr/share/nmap/scripts/`

## Usage

To list available scripts' categories simply run the program without any arguments:  
```bash
$ ./nmap_scripts_finder
Enter a category to search for NMAP scripts
Available categories:
"auth"
"broadcast"
"brute"
...
```

Find scripts of category `foo`:  
```bash
$ ./nmap_scripts_finder foo
Available in NMAP scripts in /usr/share/nmap/scripts/'
Category : foo
...
```

## Installation

1. `git clone https://github.com/Zhindonm/nmap_scripts_finder.git`
2. `chmod +x nmap_scripts_finder`


