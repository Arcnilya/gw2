# gw2
Guild Wars 2 CLI tool

1. clone the repository and change to the gw2 directory
2. create a file called "api_key" with your API key from account.arena.net/applications
3. make the script executable with: sudo chmod +x gw2tool

Usage:

./gw2tool list characters

./gw2tool inventory \<character>

./gw2tool equipment \<character>

./gw2tool bank 0

./gw2tool bank 1

./gw2tool daily fractals


To use "gw2tool" instead of "./gw2tool" 

export PATH=/my/directory/to/this/script:$PATH
