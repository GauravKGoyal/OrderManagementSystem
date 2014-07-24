OrderManagementSystem
=====================

Here i will try to build a simple order management system for a vendor. My vendor has a clothes store that he would like to sell on his online store. He would like to sell various garments such as pants, shorts, socks, shirts, jackets, sweter, etc.
Each garment has various characterstics such as colour, size, etc.  

There would be following roles in the site
Vendor -
vendor should be able to upload a particular garment with its characterstics. Note characterstics may vary from garment to garment so they should be dynamic.
Vendor should be able to remove and existing garment.
Vendor should be able to see the list of orders that needs to be processed

Visitor -
visitor should be able to view all the available garments
visitor would be able to search for a particular kind of product or use navigation system 

customer -
Customer should be able to sign up and log in
Customer should be able to buy any of the product by placing an order


Technology Phase 1
In the begning all the calls will be synchronous which means where user places an order and order on the server took some time to process it then user will be stuck on the same screen for that period of time.
Support for workload tracking for scalability reasons.
Support for error tracking for better usage.
Support for multiple vendors - consider multi tenant tech
Make use of MVC 5 with Razor syntax
Make use of boot strap for website desining

Technology Phase 2
Remake this website using Angular JS




