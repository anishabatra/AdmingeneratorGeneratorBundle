# Symfony2 Bundle

This package is a symfony2 admin generator based on YAML conf and twig template

This package is inspired from fzaninotto/Propel2


# Run a test

## Install the bundle in a Symfony2 project src/ dir

## Configure the bundle

In AppKernel.php

```php
   $bundles[] = new Admingenerator\GeneratorBundle\AdmingeneratorGeneratorBundle(),
   $bundles[] = new Admingenerator\DemoBundle\AdmingeneratorDemoBundle(),
```
And after you can edit the DemoBundle/Resources/config/generator.yml file to see changes

In your browser :

http://admingen.local/app_dev.php/admin-demo/


