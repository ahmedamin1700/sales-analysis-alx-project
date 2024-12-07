# Sales Analysis ALX Project

## Data Structure (metadata)

### Outlets table
- `outletId` id identifier for the outlet
- `outlet Name` outlet name
- `Outlet Class` outlet class values `تجزئه- بقالة`, `جمله غذائى`, `تجزئه- منظفات` `جمله منظفات`
- `Outlet Type`	between `تجزئه` and `جمله` (cleaning needed for uniqueness)
- `Employee_Code`	employee id
- `Employee_Name`	employee name
- `Warehouse Code` warehouse id
- `Warehouse Name` warehouse name

### Products table
- `Product ID` product id
- `Product Code` product identifier code
- `Product Name` product name
- `Category` between `Detergent`, `Soap` and `Shower gel`
- `subcategory` subcategory
- `Price` each product price

### Reps table
- `ID` each representative id
- `Name` name for representative
- `Username` 
- `Role` salesperson
- `ZONE` zone for each representative `Delta` `Upper` `Cairo/Giza`
- `Distributor` id for each distributer.

### Sales table
- `Date` date item sold
- `Sub_Db_Name` warehouse name
- `Username` representative id
- `Name_Of_The_User` name for representative
- `Outlet_Id` id identifier for the outlet
- `PRODUCT_CODE` product id
- `Product Name` product name
- `Quantity` sold quantity (some item quantities with negative sign)
- `Price_Per_Piece`	item price
- `Total Price` sold * item price (could be deleted and maintained by power bi)

### Visits table
- `DB Name` warehouse name
- `Sales Rep ID` each representative id
- `Sales Rep Name` name for representative
- `Date` date of visit
- `Classification` for `Outlet Type` between `تجزئه` and `جمله`
- `Store Code` id identifier for the outlet
- `Visit Starting Time` visit starting time
- `Visit Ending Time` visit ending time
- `Sale Amount` amount sold in visit time

### Warehouse table
- `Warehouse Name` warehouse name
- `Code` warehouse code
- `Region` warehouse region



