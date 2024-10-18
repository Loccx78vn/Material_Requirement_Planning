# Tutorial to implement MRP in R:
Today, we will learn about what is MRP - Material Requirment Planning, how its important role in supply chain management and way to implement it in R. This post will introduces essential inventory management concepts, including Material Requirements Planning (MRP), Safety Stock, and Reorder Point (ROP), along with step-by-step instructions on implementing them in R.

## Material Requirements Planning (MRP):
A planning system to determine what materials are needed, in what quantity, and when. 
- Inputs: Master Production Schedule (MPS), Bill of Materials (BOM), and Inventory Status.
- Outputs: Planned orders for raw materials and components.

## Safety Stock:
Safety stock is extra inventory held to mitigate the risk of stockouts due to variability in demand or lead time. It acts as a buffer against unexpected increases in customer demand or delays in supplier deliveries.

## Reorder Point (ROP):
The inventory level at which a new order is placed. The simple equation of calculating ROP is the mean demand x leadtime + safety stock.

# Practice in R:
- Step 1: Install necessary libraries like dplyr and tidyverse.
- Step 2: Create data frames for demand, lead time, and inventory records.
- Step 3: Calculate safety stock using statistical functions.
- Step 4: Build an ROP function to automate reorder point calculation.
- Step 5: Integrate MRP logic using BOM and lead time data.

![](img/poster)
