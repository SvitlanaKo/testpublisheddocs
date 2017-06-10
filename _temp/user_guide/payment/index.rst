.. _user-guide--payment:

Payment
=======

To facilitate global B2B sales, OroCommerce administrator enables valid payment methods for particular locations and integrates local payment providers or the best payment options whenever it is possible.

When submitting an order, the customer may have several payment options to choose from. They depend on the payment address that is collected at the checkout. Once address is provided, OroCommerce evaluates payment methods against the special payment rules and exposes only the options recommended for the particular location and/or based on other order details. After the customer user has selected the payment method, they are prompted to enter payment details and proceed to the checkout.

Depending on the payment method, payment may be processed immediately or may be delayed for the pre-configured period of time, or until a particular event (e.g. until the order is ready for delivery).

After the payment details were provided, the sales person can view the payment history, and capture the delayed payment.

When the payment term is selected, the payment is considered to be captured in full and the payment information is not available.

Payment Providers Overview
--------------------------

OroCommerce supports the following payment provider services. Follow the link for detailed description:

* :ref:`Check/Money Order <money_order_overview>`
* :ref:`Payment Term <user-guide--payment--payment-providers-overview--payment-term>`
* :ref:`PayPal <user-guide--payment--payment-providers-overview--paypal>`
* :ref:`Authorize.Net <user-guide--payment--payment-providers-overview--authorizenet>`
* :ref:`Wirecard <doc--payment--payment-providers-overview--wirecard>`
* :ref:`InfinitePay <user-guide--payment--payment-providers-overview--infinitepay>`

Payment Integration Prerequisites
---------------------------------

Before you can start using a payment service in OroCommerce, you might perform a preliminary preparation steps (like sign up for a service and configure integration on the service provider side). See details on the necessary steps here:

* :ref:`PayPal <user-guide--payment--prerequisites--paypal>`
* :ref:`Authorize.Net <user-guide--payment--prerequisites--authorizenet>`
* :ref:`Wirecard <doc--payment--prerequisites--wirecard>`
* :ref:`InfinitePay <user-guide--payment--prerequisites--infinitepay>`

Configuration
-------------

In OroCommerce, perform the following configuration:

* Set up a :ref:`merchant location <sys--conf--commerce--payment--general>`
* Create an integration with the service provider:

  * :ref:`Check/Money Order <sys--integrations--manage-integrations--check-money-order>`
  * :ref:`Payment Term <sys--integrations--manage-integrations--payment-term>`
  * :ref:`PayPal Payflow Gateway / PayPal Payment Pro <sys--integrations--manage-integrations--paypal-payflow-gateway>`
  * :ref:`Authorize.Net <user-guide--payment--configuration--payment-method-integration--authorizenet-details>`
  * :ref:`Wirecard Checkout Seamless <doc--payment--configuration--payment-method-integration--wirecard>`
  * :ref:`InfinitePay <sys--integrations--manage-integrations--infinitepay>`

  See quick introduction into the :ref:`Payment Method Integration overview <sys--integrations--manage-integrations--payment-methods>`.

* Configure :ref:`payment rule <sys--payment-rules>` to enable the integrated payment methods for your customers.

Preview of the Payment Information During the Checkout
------------------------------------------------------

.. include:: /user_guide/payment/checkout/index.rst
   :start-after: begin
   :end-before: finish

.. toctree::
   :maxdepth: 3
   :hidden:

   payment_providers_overview/index

   prerequisites/index

   configuration/index

   checkout/index
