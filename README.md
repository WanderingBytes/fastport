# fastport
This is a simple binary I wrote to automate nmap in a robust efficient way.
It will take a host as an argument then do a fast nmap port discovery scan to get a list of all ports open quickly, then it will forward those ports into another nmap scan that will do a more aggresive scan. Saving time ultimately.  

## Installation

All one must do is download and put the binary into there bin folder of choice.


example : "curl https://raw.githubusercontent.com/WanderingBytes/fastport/main/fastport -o /bin/" (or the bin folder of choice, just make sure it is in your path variable)

### Usage
fastport [ip or host]
