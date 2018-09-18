# drupal-commerce-pointcheckout
PointCheckout Payment extension for Drupal commerce on Drupal 7 

# Installation steps :

1. download the lastest release tar.gz file from the [releases section](https://github.com/pointcheckout/drupal-commerce-pointcheckout/releases)
2. Next in  your store admin portal, go to  **Site settings** -> **Advanced settings** -> **Modules** and install the extension
    * if you are unable to install the extension from the admin panel, you can extrat the extension tar.gz and copy the commerce_pointcheckout folder into [your site root]/sites/all/modules/ 
3. after installing the extension, enable the commerce(PointCheckout) module under **Site settings** -> **Advanced settings** -> **Modules** and then click on **Save configuration**


# Enabling and configuring PointCheckout extension:
1. under  **Store settings** -> **Advanced store settings** -> **Payment methods** you should see the payment method **pointcheckout pay**
2. for the payment method **pointcheckout pay** click on the **edit** button, then under the **Actions** section click on the **edit** button.
3. In the **Payment settings** panel, select the mode for your payment Integration, **Test** mode is used to test the extension, Change to **Live** when testing is done.
4. In the **Payment settings** panel, Fill in the **API Key** and **API Secret** provided by PointCheckout
    * note that the API Key and Secret provided for the Test mode will not work for the Live mode and viseversa.
5. go back to **Store settings** -> **Advanced store settings** -> **Payment methods** and click on the **enable** button next to **pointcheckout pay**
