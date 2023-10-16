# Bike_Stores_MSSql_Project4_Dropping_Objects

This projects showcases my ability to drop tables and schemas in MSSql using the BikeStores database.

The BikeStores database is a sample database that can be used for learning and practicing SQL queries. It models a bike store's operations, including categories, brands, products, customers, stores, staffs, orders, order items, and stocks.

Name   : BikeStores
Link   : http://www.sqlservertutorial.net/load-sample-database/

Below is the breakdown of the MS SQL queries used in this project:
- DROP TABLE IF EXISTS sales.order_items;: Drops the table "order_items" in the "sales" schema if it exists.
- DROP TABLE IF EXISTS sales.orders;: Drops the table "orders" in the "sales" schema if it exists.
- DROP TABLE IF EXISTS production.stocks;: Drops the table "stocks" in the "production" schema if it exists.
- DROP TABLE IF EXISTS production.products;: Drops the table "products" in the "production" schema if it exists.
- DROP TABLE IF EXISTS production.categories;: Drops the table "categories" in the "production" schema if it exists.
- DROP TABLE IF EXISTS production.brands;: Drops the table "brands" in the "production" schema if it exists.
- DROP TABLE IF EXISTS sales.customers;: Drops the table "customers" in the "sales" schema if it exists.
- DROP TABLE IF EXISTS sales.staffs;: Drops the table "staffs" in the "sales" schema if it exists.
- DROP TABLE IF EXISTS sales.stores;: Drops the table "stores" in the "sales" schema if it exists.
- DROP SCHEMA IF EXISTS sales;: Drops the schema "sales" if it exists.
- DROP SCHEMA IF EXISTS production;: Drops the schema "production" if it exists.

These queries are used to remove any existing tables and schemas from the BikeStores database. It is commonly used when resetting or cleaning up a database before recreating or reimporting data.
