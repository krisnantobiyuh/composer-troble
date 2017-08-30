# having-troble-install-composer

To download / install on MacOSX, you can do the following steps or try the homebrew steps below:

Goto a directory you can write to:

``` 
cd ~ 
```
get composer:

``` 
curl -sS https://getcomposer.org/installer | php 
```
move composer into a bin directory in your $PATH var:

``` 
sudo mv composer.phar /usr/local/bin/composer
```
double check composer works

```
composer about 
```
(optional) Update composer:

``` 
sudo composer self-update
```

by. https://stackoverflow.com/questions/14437588/having-trouble-installing-composer
