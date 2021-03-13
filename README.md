Module Post OpenCart 3.0
-----------------------------------------------

Parameters used by the post office:
--------------------------------

[Visit:] (http://www.correios.com.br/para-voce/precisa-de-ajuda/limites-dimensoes-e-de-peso)

Note: Sedex today has weight and maximum dimensions smaller than that monthly by the post office.

Requirements
----------
1 - PHP ^ 5.6

2 - [Switcher Template] (https://www.opencart.com/index.php?let=marketplace/extension/Info&Extension_Id=31589&filter_member=jneuhoff)

Installation
----------

1 - Install the module by admin (extensions -> installer).

2 - Set the Post Module options (Extensions -> Freets).

Comments:
-----------

1) The values ​​of freights obtained directly from the Post Office site are estimates that must be confirmed at the time of posting.

2) For the correct module operation, the correct registration of the dimensions and weights of the products is essential.
   The dimensions can be in millimeters or centimeters. Weight in grams or kilograms.

3) If the Post Offices do not appear, refer to the OpenCart error log for more details.

4) Not every CEP is covered by some services such as SEDEX 10. In this case, the delivery option of this service will not appear for the customer.

NOTE:
-----------

> The system is not yet fully ready, there is no error treatment. Study the code and test before placing production.

More common mistakes
-----------

*** Post Office does not appear in the store ***

Several reasons can contribute to the post office does not appear in the delivery options:

-> CEP of incorrect origin and destination
-> Dimensions and weights of blank products or out of postcards
-> currency (real) not configured in the store
-> Problems with the webservice of the post office (in this case there is not much to do but wait for the service to return to normality)
-> Incorrect installation of the module for the version of your store.

----------------------------
Doubts, suggestions and warnings about bugs Access the topic of the module in the Forum of the Opencart Brasil:
http://forum.opencartbrasil.com.br/

----------------------------

Original design of:
Júlio César Campos Guimarães
