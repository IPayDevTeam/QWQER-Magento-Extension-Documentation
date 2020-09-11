## QWQER Extension Documentation (Magento 2)

### Installation

1. Download extension [qwqer-module.zip](https://github.com/IPayDevTeam/QWQER-Magento-Extension-Documentation/raw/master/extensions/qwqer-module.zip)
2. Install module by below ssh commands:
```
$ bin/magento module:enable Qwqer_Delivery
$ bin/magento setup:upgrade
$ bin/magento cache:clean
```



### Configuration / Activation

1. Go to page: **Store > Configurations > General > QWQER Settings**
2. Type your QWQER merchant's credentials (**login** and **password**)
3. Type **your store's address** (you can add **additional addresses** if you want)
4. Change status to **Enabled** and save the form
5. Now module are configured and activated

### Usage
On the orders page are now new tab **Ship by QWQER**

If you want to ship products via QWQER, you must select this tab.

The content of the tab hav **3 sections**:
- **Pick up address (Your store's address):** Here are your store's address.
- **Delivery address (Order shipping address):** Shipping destination, you able to change fields with your needs.
- **Delivery price:** Each QWQER order must be calculated first, so if you have changed some fields, you must recalculate price of delivery, and only after that you can accept order delivery.

Also there are additional button **Process delivery**, by clicking it, QWQER delivery will be created and exchange will be included to the QWQER's invoice later.

After QWQER order created successfully do not forget to change store's order status to **Shipping in progress** or something similar.
