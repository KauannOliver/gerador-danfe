# **DANFE Generation System**

This project was designed to assist administration classes at Senac by providing a streamlined system for generating DANFEs. It simplifies the invoice issuance process with an intuitive interface and automated features.

---

## **MAIN FEATURES**

### 1. **Issuer and Recipient Data Entry**
   - Users can enter essential details, including company name, CNPJ/CPF, state registration, and address.
   - Integrated with the Correios ZIP code API to auto-fill address fields, enhancing efficiency and reducing errors.

### 2. **Transport Details**
   - Captures transport information such as carrier name, CNPJ, state registration, and freight details.
   - Allows assignment of freight responsibility, calculation of total transport costs, and inclusion of product weight.

### 3. **Product Module**
   - Enables users to add items to the DANFE, with fields for:
     - Product code, description, quantity, unit price, and discount.
   - Automatically calculates the total for each item, factoring in any applicable discounts.

### 4. **Responsive User Experience**
   - Built with Bootstrap and jQuery for a user-friendly, responsive design.
   - Field masking for CNPJ, phone, and ZIP code fields reduces errors and ensures accurate data input.

### 5. **DANFE Generation**
   - Generates a complete, printable DANFE that organizes all entered information in a clear and accessible layout.
   - Designed for use as a fiscal document, ready for immediate application.

---

## **TECHNOLOGIES USED**

### 1. **HTML and Bootstrap**
   - Provides a structured, responsive interface for ease of use.

### 2. **JavaScript and jQuery**
   - Powers field automation and integration with the Correios ZIP code API.

### 3. **JSON**
   - Used for temporary data storage and handling during DANFE generation.

---

## **CONCLUSION**

The **DANFE Generation System** is a valuable tool for teaching administrative processes, simplifying invoice creation with intuitive data entry and automation. By integrating issuer, recipient, transport, and product details into a printable format, the system ensures accuracy and efficiency, making it a practical solution for academic and professional use.
