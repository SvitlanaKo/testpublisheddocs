.. _user-guide--payment--prerequisites--infinitepay:

Prerequisites for InfinitePay Integration
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To start using InfinitePay with OroCommerce application, do the following:

1. Contact https://www.infinitepay.de/ and sign up for their services.

   .. image:: /user_guide/img/payment/prerequisites/infinitepay/infinitepay_contact.png

2. From the InfinitePay support team, obtain the following credentials:

   * **Client Reference** --- The unique identifier of your InfinitePay account.
   * **Username** --- Login for your InfinitePay account that is used to authenticate OroCommerce calls to the InfinitePay API.
   * **Password** --- Password that is used to authenticate OroCommerce calls to the InfinitePay API.
   * **Secret For Security Code** --- This is a pre-shared key used to cipher payment information.

   You will use these credentials to set up the integration between InfinitePay and OroCommerce.

#. In your Oro Management Console, configure an integration with InfinitePay. See the :ref:`InfinitePay Integration <sys--integrations--manage-integrations--infinitepay>` topic for more information. You can configure several integrations with different sets of options to enable multiple InfinitePay payment methods for checkout.

#. In your Oro Management Console, configure a payment rule that defines conditions under which the configured payment method is available during checkout. For example, InfinitePay should be available only for the customers from the countries that InfinitePay supports. See the :ref:`Payment Rules <sys--payment-rules>` topic for more information.

#. To enable payments via InfinitePay for the customer users, ensure that you have captured customer's VAT ID and have configured customer's Payment Term that reflects your agreement on the allowable payment delay (see :ref:`Create a Customer <user-guide--customers--customers--create>` topic for more details).

.. note::

   InfinitePay covers financial risks in more that 40 countries. To use InfinitePay service, customer's billing address stated in the order should be in one of the countries InfinitePay supports.

   The Customer user email in OroCommerce should match buyer's personal information registered with the InfinitePay.

Now you are ready to accept card payments with the InfinitePay protection.