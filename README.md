# To compile
gcc -o fileonly-cat fileonly-cat.c
gcc -o file-n-stdin-cat file-n-stdin-cat.c

# To Note the difference
- `<a-cat> test.txt`        —> empty stdin, `<a-cat>` loads content from file
- `<a-cat> < test.txt`      —> read content from stdin

# notes
- the `fileonly-cat` program does not support reading from stdin unless its source is modified
