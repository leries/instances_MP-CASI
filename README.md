# instances_MP-CASI
In this repository, we provide the instances used in our paper "Optimizing assortment and inventory on shelves when products perish".

The **instances for each product/shelf life category** (ultra-fresh, fresh, semi-fresh) that are used in Sections 5.2(a), 5.3, 5.4(b), and 5.5 contain the parameters for the base case (see Section 5.1) and are in xlsx format. Each instance contains 30 products and the corresponding data for each parameter can be directly read in the file.

The **benchmark instances** (csv) have the following structure:
+ Each row contains data for one product and one instance consists of 50 products, i.e., each csv file has 50 rows
+ Column 1: Expected demand
+ Column 2: Standard deviation of demand
+ Column 3: Space-elasticity
+ Column 4: Sales price
+ Column 5: Unit cost
+ Column 6: Salvage value
+ Column 7: Stockout cost
+ Column 9: Product width
+ Column 11: Min. number of facings
+ Column 12: Max. number of facings
+ Column 14: Stock per facing
