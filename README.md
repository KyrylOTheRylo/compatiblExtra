# Enterprise Software Development in Python

## course info
_____________________________________________________________________________

This project includes examples used for the summer course
**Enterprise Software Development in Python by CompatibL**.

Large scale, enterprise quality Python software cannot be built by throwing
together  scripts and Jupyter notebooks. This four lecture course covers
design patterns and best practices for building high quality professional
software packages in Python.

Course material includes:

* Best practices in using classes and inheritance
* Best practices in testing and unit test frameworks - unittest, pytest
* Best practices for working with complex data – dataclass, attrs, pydantic
* Working with SQL databases - sqlalchemy
* Working with document databases - MongoEngine
* Designing and responsibly versioning microservices - FastAPI
* Building web apps - Flask and Bottle
_____________________________________________________________________________
 My Upgrades:
 
 * In classes RelationalTrade and TreeTrade:
 
   1. Add a new attribute called notional with type float that will be saved in 
   the database with the trade.

 * In relational_crud_test.py and tree_crud_test.py:
   1. Specify notional of 100, 200, and 300 respectively for the three trades loaded into the database.
   2. Add query for trades with notional >= 200 to result.
   
 * In fastapi_blotter.py:
   1. Specify notional of 100, 200, and 300 respectively for the three trades loaded into the database.
   2. Add new function query_by_notional using with a single optional parameter min_notional.
   3. Provide implementation of this function to return the trades with 
      notional >= min_notional if min_notional is specified, and all trades otherwise.

 * In requests_blotter.py:
 
   1. Add code to test query_by_notional both with and without the min_notional parameter.
 
