# Danfe Generation System

This project was developed to support administration classes at Senac, providing an intuitive system for generating DANFEs. It allows essential information entry, making the invoice issuance process more straightforward.


MAIN FEATURES

1. The system allows complete entry of issuer and recipient data, such as company name, CNPJ/CPF, state registration, and address. Integrated with the Correios ZIP code API, it automatically fills in addresses for added efficiency.

2. It includes transport details, such as carrier name, CNPJ, state registration, and freight. Users can assign freight responsibility, calculate total costs, and include product weight.

3. The product module allows items to be added to the DANFE, with fields for code, description, quantity, unit price, and discount. The system calculates the total for each item, applying any discounts.

4. Using Bootstrap and jQuery, the system offers a responsive and user-friendly experience. Masking is applied to CNPJ, phone, and ZIP fields, reducing errors and improving data accuracy.

5. Once filled, the system generates a complete DANFE for printing, organizing all information in an easily viewable layout, ready for use in fiscal documents.


TECHNOLOGIES USED

1. HTML and Bootstrap: Structure and responsive interface design.
2. JavaScript and jQuery: Field automation and integration with the ZIP code API.
3. JSON: Temporary storage and data handling for DANFE generation.


CONCLUSION

The DANFE generation system is a practical tool for administration classes, simplifying the creation of invoices and integrating issuer, recipient, transport, and product details into an accessible, printable format.
