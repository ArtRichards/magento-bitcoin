Bitcoin Currency For Magento, for use with Payment Gateways such as BitPay
==================================
This is a Bitcoin currency module for Magento.


Current Features
---------------------------

- New bitcoin currency and symbol. Full currency support in Magento.
- Currency conversion and conversion rates management. Manually, or daily weighted value from Bitcoincharts service.
- Scheduled conversion rates update is supported.


Installation
-----------------------------------------------------
I plan to add better documentation to the Wiki. Please be sure to backup files and data before modifying your Magento instance.

- Copy the files from this project into your Magento root.
- Enable BTC currency for your store.
- Go to Manage Currencies and import exchange rates.

## Notes:

- Magento doesn't provide a good way to override locales, so the core Zend locale files are overwritten.
- You must use the EN locale. As of now, only the EN locale is modified. I'm happy to pull new locales.


Feedback & Contributing
---------------------------
All feedback is welcome. I'm especially looking forward to feedback from Magento store owners. If you have a feature you'd
like to see implemented please let me know.

Developers, please feel free to comment and contribute. I'll gladly pull reasonable changes and you will be credited.



DONATIONS
---------------------------
This is the original bitcoin-magento developer's donation message:
"""
If you find this module useful please consider donating an appropriate amount. It helps me justify the time spent coding
to my wife and two daughters! :)

12rJSmj7Ny5LzDGkgfauC2T8TZuwNZ3xaC
"""


Licensing
---------------------------

Copyright 2014, Art Richards
Copyright 2011, Ticean Bennett

This work is licensed under the Open Software License (OSL 3.0)

http://opensource.org/licenses/osl-3.0.php
