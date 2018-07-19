## Codealist - Disable Product URL on Cart Items

### Introduction

The following extension shows you how to use action and arguments to modify the base parameters of a specific block.
In this example, we will set the "ignoreProductUrl" value to "true".

That value can be found on /Users/fsspencer/Documents/Projects/magento2/extension-dev/docroot/vendor/magento/module-checkout/Block/Cart/Item/Renderer.php

You will notice that it has a setter and getter for that attribute, so that gives us the possibility to 
modify the value from a layout update.

This update has been performed on Codealist/DisableCartItemsProductLink/view/frontend/layout/checkout_cart_item_renderers.xml

### Installation

1. Create the directory Codealist/DisableCartItemsProductLink inside app/code
2. Clone this repository into the directory you just created
3. Run `php bin/magento setup:upgrade` from your project root

