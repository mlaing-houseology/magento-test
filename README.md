# Magento - Technical Test

## Scenario

You have been asked to create a Magento 1 extension to add a block to the homepage of the website. The block will show a random quote from a list of quotes stored in the database - your extension should create this database table and handle the retrieval of quotes from it.

You will need to provide the following functionality:

* Show the random quote block ONLY on the homepage.
    * Select a random quote from the database to show in the block.
    * Quote selected in the database can be forced to a specific quote by passing the quote id as a param in the url. e.g http://DOMAIN/quoteid/1

Your database table should be structured in the following way;

### homepage_quotes

id | name    | quote              
-- | ------- | ---------------------------------------------------------------------------------------------------
1  | Quote A | It has become appallingly obvious that our technology has exceeded our humanity. - Albert Einstein    
2  | Quote B | I do not fear computers. I fear lack of them. — Isaac Asimov
3  | Quote C | Never trust a computer you can’t throw out a window. — Steve Wozniak
4  | Quote D | Everything is designed. Few things are designed well. — Brian Reed
5  | Quote E | Simplicity is about subtracting the obvious and adding the meaningful. — John Maeda
