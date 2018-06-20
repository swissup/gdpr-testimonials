# GDPR for Testimonials module

### Installation

```bash
cd <magento_root>
composer config repositories.swissup composer http://swissup.github.io/packages/
composer require swissup/gdpr-testimonials:dev-master --prefer-source
bin/magento module:enable Swissup_GdprTestimonials
bin/magento setup:upgrade
```
