##E-commerce Database Design
Introduction
This repository contains the design and implementation of a database for an e-commerce platform. The database is designed to store information about products, brands, categories, sizes, colors, and attributes.
## Database Design
The database consists of the following tables:
* product: stores general product details (name, brand, base price)
* product_item: represents purchasable items with specific variations (size, color)
* product_variation: links a product to its variations (size, color)
* size_option: lists specific sizes (S, M, L, 42)
* size_category: groups sizes into categories (clothing sizes, shoe sizes)
* color: stores available color options
* product_attribute: stores custom attributes (material, weight)
* attribute_category: groups attributes into categories (physical, technical)
* attribute_type: defines types of attributes (text, number, boolean)
* brand: stores brand-related data
* product_category: classifies products into categories (clothing, electronics)
## ERD
The Entity-Relationship Diagram (ERD) for the database can be found here.
## SQL Schema
The SQL schema for the database is included in the ecommerce.sql file.
## Usage
To use this database, follow these steps:
1. Clone the repository to your local machine.
2. Create a new MySQL database.
3. Run the SQL script in the ecommerce.sql file to create the database schema.
4. Populate the database with sample data.
## Contributing
Contributions are welcome. To contribute, please follow these steps:
1. Fork the repository to your own GitHub account.
2. Make changes to the code.
3. Submit a pull request with a brief description of the changes.
## License
This repository is licensed under the MIT License.
ecommerce.sqlecommerce.sql
