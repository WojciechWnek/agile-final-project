 ### User Stories  

Sprint/Product Backlog (Enhancements)

Story 1 (Create): As a catalog administrator, I need the ability to create a product in the catalog so that new inventory is available to customers.

Story 2 (Retrieve): As a customer, I need the ability to retrieve a product from the catalog so that I can view its details.

Story 3 (Update): As a catalog administrator, I need the ability to update a product in the catalog so that the product information remains accurate.

Story 4 (Delete): As a catalog administrator, I need the ability to delete a product from the catalog so that discontinued items are no longer visible.

Story 5 (Like): As a customer, I need the ability to Like a product in the catalog so that I can express my positive interest in the item.

Story 6 (Dislike): As a customer, I need the ability to Dislike a product in the catalog so that I can provide feedback on items I don't prefer.

Icebox (Enhancements)

Story 7 (List): As a customer, I need the ability to list all products in the catalog so that I can browse the entire inventory. (Move to Icebox)

Story 8 (Query): As a customer, I need the ability to query a subset of products in the catalog so that I can easily find specific types of items. (Move to Icebox)

Product Backlog (Technical Debt)

Story 9 (Cloud): As a developer, I need the catalog to be hosted in the cloud so that the application is highly available and scalable. (Label: Technical Debt)

Story 10 (Automation): As a developer, I need automation to deploy new changes to the cloud so that our release process is fast and reliable. (Label: Technical Debt)
   
 ### Acceptance Criteria  
   
Story 1: Create a product

Given the administrator is on the catalog dashboard
When they submit valid product details (name, price, description)
Then a new product should be created and saved in the catalog

Story 2: Retrieve a product

Given a product exists in the catalog with a specific ID
When a customer requests the product using that ID
Then the system should return the complete details of that product

Story 3: Update a product

Given a product exists in the catalog
When the administrator modifies the product's price and saves
Then the product in the catalog should reflect the newly updated price

Story 4: Delete a product

Given a product exists in the catalog
When the administrator selects the product and confirms deletion
Then the product should be permanently removed from the catalog

Story 5: Like a product

Given a customer is viewing a specific product
When they click the "Like" button
Then the total like count for that product should increase by one
