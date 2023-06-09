# HeroBannerSlider

### Features
* It displays a slider with multiple banners on the Home Page.
* This slider can have different types of banners like photo banners, video banners, YouTube banners, and Vimeo banners.
* Website visitors can easily navigate to the previous or next banner by clicking on the navigation dots or arrows.
* The admin can show specific banners to specific customer groups.
* The admin can add a URL so the customer can be navigated to that page upon clicking the banner.
* Admin can create new banners for the home page slider and he can set the duration for the banner slider to show the next banner.
* Also, he can set start and expiry dates for a banner displayed in the slider.


## Installation

1. Please run the following command
```shell
composer require arslanfarrukh/hero-banner-slider
```

2. Update the composer if required
```shell
composer update
```

3. Enable module
```shell
php bin/magento module:enable ArslanFarrukh_Core
php bin/magento module:enable ArslanFarrukh_HeroBannerSlider
php bin/magento setup:upgrade
php bin/magento cache:clean
php bin/magento cache:flush
```
4.If your website is running in product mode the you need to deploy static content and
then clear the cache
```shell
php bin/magento setup:static-content:deploy
php bin/magento setup:di:compile
```




