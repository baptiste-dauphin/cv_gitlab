# Installation

## Preparing environment
Get .deb package 
https://pandoc.org/installing.html
Should redirect to this
https://github.com/jgm/pandoc/releases/latest
Then, install it
```
sudo dpkg -i .deb
```
install all LaTeX dependencies (~800Mo)
```
apt install texlive
```


## Usage
Pandoc will automatically set parameters using extension of input and output files
```
pandoc ./index.md  -o ./cv_baptiste_dauphin.pdf
```
