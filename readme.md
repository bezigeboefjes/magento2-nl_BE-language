# Magento 2 Dutch (Belgium) Language Pack (nl_BE)

Dutch (Belgium) Magento 2 translations for Magento 2 (CE), translated, optimized by and forked from Adwise - Your Digital Brain.

[![Latest Stable Version](https://poser.pugx.org/bezigeboefjes/language-nl_be/v/stable)](https://packagist.org/packages/bezigeboefjes/language-nl_be) [![Total Downloads](https://poser.pugx.org/bezigeboefjes/language-nl_be/downloads)](https://packagist.org/packages/bezigeboefjes/language-nl_be) [![Monthly Downloads](https://poser.pugx.org/bezigeboefjes/language-nl_be/d/monthly)](https://packagist.org/packages/bezigeboefjes/language-nl_be)

### Configure Magento backend
* Activate language (backend): Account > Settings > Account information > Interface Locale
* Activate language (frontend): Stores > Settings > Configuration > [storeview] > Locale options > Locale

### Installation (manual)
* Clone repository to ``app/i18n/bezigeboefjes/nl_be/`` 
* Upgrade Magento installation ``$ php bin/magento setup:upgrade``
* Clear Magento cache``$ php bin/magento cache:clean``
* Deploy Static Content ``$ php bin/magento setup:static-content:deploy nl_BE``

### Installation (Composer)
* Require via Composer CLI ``$ composer require bezigeboefjes/language-nl_BE``
* Upgrade Magento installation ``$ php bin/magento setup:upgrade``
* Clear Magento cache``$ php bin/magento cache:clean``
* Deploy Static Content ``$ php bin/magento setup:static-content:deploy nl_BE``

### Roadmap
* Translate missing content (50% left)
* Optimize translations (in context for better experience)

### Bugs
There are still missing some translations, due to a bug in the i18n:collect-prhases method. More information about this bug can be found on: https://github.com/magento/magento2/issues/2630. This issue will be fixed in Magento CE 2.1.0 but is already fixed in develop branch.

Please report all bugs/optimizations in Github!

