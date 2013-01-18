# Misc assets for use in various projects

## Requirements



## Installation

### Add bundle to your composer.json file

``` js
// composer.json

{
    "require": {
		// ...
        "icode4food/miscassets-bundle": "*"
    }
}
```

### Add bundle to your application kernel

``` php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new Icode4food\JqueryUiBundle\Icode4foodMiscAssetsBundle(),
        // ...
    );
}
```

### Download the bundle using Composer

``` bash
$ php composer.phar update icode4food/miscassets-bundle
```


## Licenses

Refer to the source code of the included files for license information
