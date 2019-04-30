# PEPPOL invoice support by large organizations
Shows which large organizations are sending invoices through the [PEPPOL-network](https://peppol.eu/what-is-peppol/) for faster processing of invoices.

## What is PEPPOL?
PEPPOL is a set of artifacts and specifications enabling cross-border eProcurement ([source](https://peppol.eu/what-is-peppol/)). **Simply said**: a means of making e.g. invoicing faster and less error-prone through a standardized data format.

Imagine receiving an invoice from a company, not having to manually put in into your bookkeeping software, but having all major fields (sender, invoice date/number, lines, totals, etc.) automatically filled out for you. A massive time-saver. PEPPOL makes this scalable at a global level.

## Contributing
If you want to add information to the tables below, feel free to create an issue or submit a PR! Easiest way is to 
1. Fork this repo.
2. Make changes (try to keep company names in alphabetical order 🤓)
3. Commit the changes to your fork.
4. Send a pull request to this repo.

## PEPPOL support per country
The tables below indicate per company whether they are able to send UBL-invoices and/or via the PEPPOL-network. Explanation of the columns:
- **Company**: The company name, in alphabetical order.
- **UBL status**: Whether the company can send UBL-invoices (in .xml format), as an alternative to PDF invoices. Allows the receiving party to import an .xml file which automatically fills out all major fields (sender, invoice date/number, lines, totals, etc.).
- **PEPPOL status**: Whether the company can send UBL-invoices through the PEPPOL-network, allowing the receiving party to automatically receive invoices in their bookkeeping software. Eliminates the need for the receiving party to upload PDF/UBL invoices into their bookkeeping software. 
- **Explanation**: Short description why the company isn't supporting UBL/PEPPOL yet, or short statement from the company that UBL/PEPPOL isn't supported yet.

### Global
|Company|UBL status|PEPPOL status|Explanation|
|---|---|---|---|---|
|[Exact Online](https://www.exact.com/uk/exact-online/)|✅|⏳|Exact Support 28-04-2019: *"Sending invoices through the PEPPOL network is possible for Exact customers since Spring 2019, while receiving invoices through PEPPOL is scheduled for the end of 2019."*|
|Microsoft (Azure/Office 365)|❌|❌| Microsoft Support 29-04-2019: *"We have an update from our accounting team that other than PDF format there is no other option in which invoices can be provided."*|

### The Netherlands
|Company|UBL status|PEPPOL status|Explanation|
|---|---|---|---|---|
|Moneybird|✅|✅||
|NS (Nederlandse Spoorwegen)|❌|❌|[Forum topic](https://community.ns.nl/ns-business-card-57/facturen-ontvangen-in-ubl-formaat-en-of-via-peppol-simplerinvoicing-57313)|