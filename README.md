# Sistemazione dexanet-theme | Input GTM

## Struttura

base.php (contiene script e noscript di GTM)

/theme-options/
- /controller/
— register.php
- /models/
— seo-options.php
- /views/
— input.php


/core/
- config.php



## base.php
1. Spostare il codice no-script al di sotto dell'apertura del tag body php
   
![Configurazione PHP](https://github.com/DahNova/fix-dexanet-theme/raw/main/base.php.jpg)  


## config.php
2. Fixare il typo nel file config.php

![Configurazione PHP](https://github.com/DahNova/fix-dexanet-theme/raw/main/config.php.jpg)  

Va cambiato da ga_tgm a seo_tgm


## register.php
3. Assicurarsi che riga 2 e 3 (ga e tgm) siano decommentate, commentare invece da 4 a 7.  

![Configurazione PHP](https://github.com/DahNova/fix-dexanet-theme/raw/main/register.php.jpg)  


## seo-options.php
4. Decommentare funzione seo_tgm_element, commentare invece le sottostanti fino a Theme Options

![Configurazione PHP](https://github.com/DahNova/fix-dexanet-theme/raw/main/seo-options.php.jpg)  


## input.php
5. Primo passaggio di configurazione  

![Configurazione PHP](https://github.com/DahNova/fix-dexanet-theme/raw/main/input.php.jpg)  

