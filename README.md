# Guild Wars 2 CLI tool

1. clone the repository and change to the gw2 directory
2. create a file called "api_key" with your API key from [ArenaNet](account.arena.net/applications)
3. make the script executable with: <code>sudo chmod +x gw2tool</code>

Usage:

<code>./gw2tool list characters</code>

<code>./gw2tool inventory \<character></code>

<code>./gw2tool equipment \<character></code>

<code>./gw2tool bank 0</code>

<code>./gw2tool bank 1</code>

<code>./gw2tool daily fractals</code>

<code>./gw2tool daily fractals tomorrow</code>

<code>./gw2tool stats \<character></code>


To use "gw2tool" instead of "./gw2tool" 

<code>export PATH=/my/directory/to/this/script:$PATH</code>
