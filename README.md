# Project 1 - Revisited
 By: Paul Montecinos
 
![LR FI](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/71a68816-5440-4784-8491-e620500be876)

### Top 3 most impactful features on the Linear Regression Model

* Item MRP 
    - It makes since that the item MRP would have the most importance since it directly affects the amount of revenue a store earns. The higher the prices are correlates to the amount of money the store makes.

* Outlet Type Grocery Store
* Outlet Type Supermarket Type 3

    - The other 2 most impactful features have to do with the outlet type. This shows sales can have positive or negative effects on the sales of a given store type. Certain outlet types may be located in easy to access areas and would typically generate more traffic leading to more sales. Also certain outlet types may have better layouts making it easier to access the things you need quicker.


![RF FI](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/beddf031-f404-41d8-8dd1-7367c4aea227)

### Top 3 most impactful features on the Random Forest model

* Item MRP 
    - As also stated in our Linear Regression model, it makes since that the item MRP would have the most importance since it directly affects the amount of revenue a store earns. The higher the prices are correlates to the amount of money the store makes.

* Outlet Type Grocery Store
    - This shows sales can have positive or negative effects on the sales of a given store type. Certain outlet types may be located in easy to access areas and would typically generate more traffic leading to more sales. Also certain outlet types may have better layouts making it easier to access the things you need quicker.
    
* Item Visibility
    - Speaking of outlet types with better layouts that also brings into question item visibility. Items that are easier to locate within a store would positively generate more sales. Items that are easier to locate would make the store a preference due to convenience of getting in and out of a store. 



![RF FI Perm](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/c486f609-e4a6-4a04-8386-bc480d3ee655)

### Top 5 most important features
* Item MRP
* Outlet Type Grocery Store
* Item Visibility
* Outlet Type Supermarket Type 3
* Item Weight


![ShapBar RF](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/cb8d0423-f5ea-4be2-8d13-28773559af2d)

### Comparison SHAP vs orginal features:
* The top 5 remained the same however Item Visibility and Supermarket Type 3 changed places. 
* Item weight decreased in comparison to the orginal features. 


![ShapDot RF](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/7bbdcfdc-e76f-4823-a9ce-f676b09d3459)

### Top 3 most important features based on the ShapDot plot
* Item MRP
    - Shows higher the MRP of an item increased our target
* Outlet Type Grocery Store
    - Grocery stores tend to decrease our target

* Outlet Type Supermarket Type 3
    - Type 3 increases our target 


![FP MRP](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/7dcc0e8d-8859-4009-95e9-05316d7deb32)

### Interpretation
 * The higher the MRP the more it pushes the target higher and at the same time the outlet type grocery store pushes the target lower



![FP MRP Min](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/fe5ad3c6-e2ca-4f66-b7aa-da5589104640)

### Interpretation
 * The lower the MRP decreases out target, while the outlet type not being equal to the grocery store actually increases our target.



![Lime MRP](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/d0e001c8-81b3-485f-90b3-42ad87dd4b1a)

### Interpretation
 * Using the Lime interpretation above we can see that higher sales predictions are positively impacted when the MRP is greater than 183.88, while also being negatively impacted by the Grocery store outlet type



![Lime MRP min](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/90d48374-f8cf-4dac-a717-150c783ad688)

### Interpretation
 * Using the Lime interpretation above we can see that higher sales predictions are negatively impacted when the MRP is equal to or lower than 98.58, while also being positively impacted by the Grocery store outlet type




![FP IV Max](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/bc8166d0-d682-40b9-8c2d-b7f1650224f1)

### Interpretation
 * The higher the item visualization the more it pushes the target higher and at the same time the outlet type grocery store pushes the target lower


![FP IV Min](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/a9230476-0002-45af-a8ac-1a220547b2cf)

### Interpretation
 * The lower the item visualization the more it pushes the target higher however not by much and at the same time the outlet type grocery store pushes the target lower


![Lime Viz Max](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/5884ab5a-d170-417e-aca4-a90e0bdb1a44)

### Interpretation
 * The items with the highest visibility are positively impacted by higher item MRPs while they tend to be negatively impacted by the outlet types




![Lime Viz Min](https://github.com/pmontecinos23/Project-1---Revisited/assets/29460152/6db28a52-50d5-43ef-9617-eb4d89373799)

### Interpretation
 * The items with the lowest visibility are negatively impacted by almost every other column with the exception of outlet type supermarket













