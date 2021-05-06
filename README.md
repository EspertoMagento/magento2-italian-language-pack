## Magento 2 Italian Language Pack

**Magento 2 Italian Language Pack** is special gift for Magento 2 Community Edition. This guide supports you to convert the default language (English) into Italian language on your entire store.

Read more [Magento 2 Italian Language Pack](https://www.espertomagent.it/shop/estensioni-magento-2/traduzioni-lingua-italiano-magento-2/)


## Overview

- Install Italian Language Pack
- How To Active Italian Language Pack

## How to Install Italian Language Pack

### ✓ #1. Composer method (Recommend)
Install the Italian language pack via composer is never easier.

**Install Italian pack**:

```
composer require espertomagento/magento2-italian-language-pack
php bin/magento setup:static-content:deploy it_IT
php bin/magento cache:clean
php bin/magento cache:flush

```


**Update  Italian pack**:

```
composer update espertomagento/magento2-italian-language-pack
php bin/magento setup:static-content:deploy it_IT
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

#### Authentication required (Optional)

![Authentication required]

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)

## How to active Italian language pack

Now time to active the Italian language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`


<!-- ## Translation process of Italian Language Pack
![process](http://progressed.io/bar/90) -->


## Supported Magento versions

- Magento v2.0.0 - Magento v2.4.x