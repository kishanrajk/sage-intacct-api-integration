# Sage Intacct API Integration (Language-Agnostic)

This repository contains example XML requests for integrating with Sage Intacct APIs. 
It covers creating:

- Invoices
- Payments
- Credit Notes

## How to Use

1. Open **Postman** or any HTTP client.
2. Set **POST URL** to: `https://api.intacct.com/ia/xml/xmlgw.phtml`
3. Set **Content-Type** to `application/xml`.
4. Copy the XML from `examples/` folder.
5. Send the request and view the XML response.

## Examples

- `create_invoice.xml` → Create an AR Invoice
- `create_payment.xml` → Create a Payment for Invoice
- `create_creditnote.xml` → Create a Credit Note

## Notes

- Replace all placeholders (YOUR_SENDER_ID, YOUR_USER_ID, etc.) with your actual Sage Intacct credentials.
- This repo is language-agnostic — you can implement it in **Python, Java, C#, JavaScript, etc.** using HTTP requests.
