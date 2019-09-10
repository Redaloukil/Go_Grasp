# Introuction

we encounter Travel Salesman Problem (TSP) in many applications and a typical first application is of course in logistics.
in this chapter we propose a web application (web service) to solve the problem of tsp and optimize a delivery journey of a deliveryman by lookin for the Hamiltonian cycle of a given set of points.


##the following steps will explain how the delivery man can do the delivery travel : 

1 - Ret the none delivred parcels (the geolocation of every parcel).
2 - Contruct the candidate list which contains a set of parcels. 
3 - Get Restrict the candidate list.
4 - Select a random candidate 
5 - remove it form candidates list 
6 - If candidates list is not empty iterate.

