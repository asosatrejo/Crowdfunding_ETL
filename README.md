# Crowdfunding_ETL

## Summary
> For the ETL mini project, you will work with a partner to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After you transform the data, you'll create four CSV files and use the CSV file data to create an ERD and a table schema. Finally, you’ll upload the CSV file data into a Postgres database.

## Requirements
1.  **A Category DataFrame is Created**
       - The DataFrame contains a "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories.
       - The DataFrame has a "category" column that contains only the category titles.
       - The category DataFrame is exported as `category.csv`

3. **A Subcategory DataFrame is Created**
    - The DataFrame contains a "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories.
   - The DataFrame contains a "subcategory" column that contains only the subcategory titles.
   - The subcategory DataFrame is exported as `subcategory.csv`

5. **A Campaign DataFrame is Created**
   - Add the correct columns,
   - The campaign DataFrame is exported as `campaign.csv`

6. **A Contacts DataFrame is Created**
   - The DataFrame has the following columns:
        - A "contact_id" column
        - A "first_name" column
        - A "last_name" column
        - An "email" column
    - The contacts DataFrame is exported as `contacts.csv`

7. **A Crowdfunding Database is Created**
   - A database schema labeled, `crowdfunding_db_schema.sql` is created.
   - A crowdfunding_db is created using the `crowdfunding_db_schema.sql` file.
   - The database has the appropriate primary and foreign keys and relationships.
   - Each CSV file is imported into the appropriate table without errors.
   - The data from each table is displayed using a `SELECT *` statement.

## Split Work
- A:
    - Create Category & Subcategory DataFrame
    - Create Contacts DataFrame
    - Majority of Read ME
- M:
    - Create Campaign DataFrame
    - Create Crowdfunding Database

## Resources
- [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
- [Quick-Start: Regex Cheat Sheet](https://www.rexegg.com/regex-quickstart.html)

## Team
Created by [Ariana S.T.](https://github.com/asosatrejo/) [A] and [Mary F.](https://github.com/) [M]
