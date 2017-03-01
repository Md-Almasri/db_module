#Design Database

Design a database that contains information about Organisations that work in the public sector. Each organisation has a name, address, borough, a list of services that it provides and a telephone number. Services include things like Immigration, Housing, Discrimination - this is not a fixed list. Each Organisation has a Contact Person who we need to maintain their contact details (name, email, telephone etc..), a Contact Person can work in more than one Organisation, and each Organisation can have more than one Contact Person with different titles and responsibilities.

Organisation data is added by a User. We need to maintain a list of Users who can have different roles. We need to be able to know which organisation was added by which user, and also who was the last user to edit it and when.

We need to be able to search for organisations by category name, organisation name or borough.

Think about:
- What tables you need?
- What are the relations about tables?
- Define the data types, primary keys, foreign keys, indexes
- Think about hypothetical scenarios - what if we delete a User, what happens to the organisations they added?
- Make your design robust
- This description is intentionally incomplete - ask questions to get clarifications if needed. 

