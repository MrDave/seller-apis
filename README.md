# Seller APIs

Scripts designed for updating items and prices on Ozon Seller and Yandex Market marketplaces.

## OZON Seller

Script `seller.py` works with Ozon Seller marketplace. It updates stocks and prices of watches with the help of an inventory spreadsheet from casio website.

To use script, the following env variables must be put down in `.env` file:

- SELLER_TOKEN - API access token for Ozon Seller marketplace
- CLIENT_ID - marketplace's client ID

## Yandex Market

Script `market.py` works with Yandex Market marketplace.
This scripts works with goods distributed via FBS (Fulfillment by Seller) and DBS (Delivery by Seller) systems. For both type of goods it gets updates stocks and prices on Yandex Market respective campaign.

To use script, the following env variables must be put down in `.env` file:

- MARKET_TOKEN - Yandex Market API access token
- FBS_ID - FBS shop (campaign) ID
- DBS_ID - DBS shop (campaign) ID
- WAREHOUSE_FBS_ID - FBS warehouse ID
- WAREHOUSE_DBS_ID - DBS warehouse ID
