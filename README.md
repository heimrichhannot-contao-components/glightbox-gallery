# Glightbox Gallery Contao component

[![Latest Stable Version](https://poser.pugx.org/heimrichhannot-contao-components/glightbox-gallery/v/stable)](https://packagist.org/packages/heimrichhannot-contao-components/glightbox-gallery)
[![Total Downloads](https://poser.pugx.org/heimrichhannot-contao-components/glightbox-gallery/downloads)](https://packagist.org/packages/heimrichhannot-contao-components/glightbox-gallery)

Shim repository for [Glightbox](https://github.com/mcstudios/glightbox) as [Contao Component](https://github.com/contao-components/installer).


## Install

```
composer require heimrichhannot-contao-components/glightbox
```


## Config

Add the following to your config (keep keys to prevent double integration):

### Contao 4

```
$GLOBALS['TL_JAVASCRIPT']['huh_components_glightbox'] = 'assets/glightbox/js/glightbox.min.js|static';
```

### Contao 3

```
$GLOBALS['TL_JAVASCRIPT']['huh_components_glightbox'] = 'assets/components/glightbox/css/glightbox.min.js|static';
```