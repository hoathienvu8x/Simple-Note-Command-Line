# Simple Note Application Using command line

This is simple note application using bash script minimal dependencies,
this app required `sqlite3` and `pandoc`

In this application `python2` is not good for `utf8` suggestion `python3+`

To install clone this repository using command

```
git clone https://github.com/hoathienvu8x/Simple-Note-Command-Line ~/.notes
```

Install dependencies

```
sudo apt-get install sqlite3 pandoc # for ubuntu
sudo yum install sqlite3 pandoc # for centos
```

Edit `.bashrc` append line using `vim` or `nano`

```
alias note='$HOME/.notes/note'
```

save and close

reload `.bashrc` using command

```
source ~/.bashrc
```

Then now using application typo command `note`


