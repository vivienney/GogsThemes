# Welcome to GogsThemes!

This repo contains styles/themes  for well known self hosted git service [Gogs](https://gogs.io/).
If you find something not displayed good  , feel free to contribute
 to make it together even better!!
 
## Steps to activate a theme:
*$GOGS_ROOT = your gogs root install location*

 
 - ````cd $GOGS_ROOT```` 
 - ```git clone https://github.com/Kos-M/GogsThemes.git```
 - ````cat ./GogsThemes/inject/head.tmpl >> templates/inject/head.tmpl  ```` 
 - ```mv ./GogsThemes/img/bg.jpg ./GogsThemes/img/wool.png public/img```
 - ```mv ./GogsThemes/themes/dark_theme.css public/css/themes```
 - ```rm -r ./GogsThemes```

## Screens
![intro]( ) ![signup]( )
![home]( ) ![repo]( )
![file]( )
 



### To disable a theme:
Just open ```$GOGS_ROOT/templates/inject/head.tmpl``` and delete 
the line contains : ``` <link rel="stylesheet" href="/css/themes/dark_theme.css">```


