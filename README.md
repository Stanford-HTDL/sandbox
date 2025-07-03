# sandbox
This repository contains three synthetic data sets.

Registry: Information about the universe of firms producing, buying, and selling an imagined commodity
  ID: unique firm identifier
  grid_x and grid_y: firm location in our synthetic flat square world
  Owner: ID of parent firm if wholly owned subsidiary
Transactions: A log of all transactions
  Buyer: The ID of the buying firm
  Seller: The ID of the selling firm
  Price: The total price of the transaction in $k
  Quantity: The total quantity of the commodity in the transaction in tons
  Distance: The distance traveled from buyer to seller
  Year: The year of the transaction
Inspections: A log of inspections for labor violations
  ID: The firm being inspected
  Violation: 1 indicates that a violation was found
  Year: The year of the inspection
  
