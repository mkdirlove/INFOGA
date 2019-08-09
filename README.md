## Infoga - Email OSINT

Infoga is a tool gathering email accounts informations (ip,hostname,country,...) from different public source (search engines, pgp key servers and shodan) and check if emails was leaked using haveibeenpwned.com API. Is a really simple tool, but very effective for the early stages of a penetration test or just to know the visibility of your company in the Internet.

## Installation

```
$ git clone https://github.com/mkdirlove/INFOGA
$ cd INFOGA
$ python setup.py install
$ python infoga.py
```

## Usage

```
$ python infoga.py --domain nsa.gov --source all --breach -v 2 --report ../nsa_gov.txt
```


```
$ python infoga.py --info m4ll0k@protonmail.com --breach -v 3 --report ../m4ll0k.txt
```

