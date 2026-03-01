# AimaneCouissi_NegotiableQuoteOrderReference

[![Latest Stable Version](http://poser.pugx.org/aimanecouissi/module-negotiable-quote-order-reference/v)](https://packagist.org/packages/aimanecouissi/module-negotiable-quote-order-reference) [![Total Downloads](http://poser.pugx.org/aimanecouissi/module-negotiable-quote-order-reference/downloads)](https://packagist.org/packages/aimanecouissi/module-negotiable-quote-order-reference) [![Magento Version Require](https://img.shields.io/badge/magento-2.4.x-E68718)](https://packagist.org/packages/aimanecouissi/module-negotiable-quote-order-reference) [![License](http://poser.pugx.org/aimanecouissi/module-negotiable-quote-order-reference/license)](https://packagist.org/packages/aimanecouissi/module-negotiable-quote-order-reference) [![PHP Version Require](http://poser.pugx.org/aimanecouissi/module-negotiable-quote-order-reference/require/php)](https://packagist.org/packages/aimanecouissi/module-negotiable-quote-order-reference)

Adds an **Order ID** link to the negotiable quote view page in the Admin for quick navigation to the order placed from that quote.

## Installation
```bash
composer require aimanecouissi/module-negotiable-quote-order-reference
bin/magento module:enable AimaneCouissi_NegotiableQuoteOrderReference
bin/magento setup:upgrade
bin/magento cache:flush
```

## Usage

Open any negotiable quote in **Admin → Sales → Quotes**. If the quote has been converted to an order, an **Order ID** link appears in the **Quote** section and navigates directly to the order view. The link is not displayed if no order has been placed from the quote.

## Uninstall
```bash
bin/magento module:disable AimaneCouissi_NegotiableQuoteOrderReference
composer remove aimanecouissi/module-negotiable-quote-order-reference
bin/magento setup:upgrade
bin/magento cache:flush
```

## License

[MIT](LICENSE)
