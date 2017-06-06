# opener

> A silly script to automate opening URLs that follow a pattern

Ever needed to open 10 URLs that follow a pattern? opener helps you automate that.

## Installation

Download the script and simply put it in your path :)

## Usage

Create a file with a list of URLs:

```
https://domain.com/search?q=laptops&color=yellow
https://domain.com/search?q=laptops&color=blue
https://domain.com/search?q=laptops&color=red
https://domain.com/search?q=laptops&color=magenta
https://domain.com/search?q=laptops&color=white
```

then run `opener path/to/my/file.txt`

You can *ofc* use env variables as well:

```
https://domain.com/search?q=$CATEGORY&color=yellow
https://domain.com/search?q=$CATEGORY&color=blue
https://domain.com/search?q=$CATEGORY&color=red
https://domain.com/search?q=$CATEGORY&color=magenta
https://domain.com/search?q=$CATEGORY&color=white
```
