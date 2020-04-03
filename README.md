Our program is to build an automaton that will be a mail-delivery robot picking and dropping off parcels. 

MeadowField:

-The village of MeadowField consists of 11 places with 14 roads within them. It can be described as array of roads as:

const roads = [
  "Alice's House-Bob's House",   "Alice's House-Cabin",
  "Alice's House-Post Office",   "Bob's House-Town Hall",
  "Daria's House-Ernie's House", "Daria's House-Town Hall",
  "Ernie's House-Grete's House", "Grete's House-Farm",
  "Grete's House-Shop",          "Marketplace-Farm",
  "Marketplace-Post Office",     "Marketplace-Shop",
  "Marketplace-Town Hall",       "Shop-Town Hall"
];

- The network of roads in the village forms a graph. The graph consists of places and roads and it is the world that our robot moves through.

TASK:
-There are parcels to various places, each addressed to some other place. The robot picks up the parcel when it comes to them and delivers when it arrives the destiantion.
-The automaton must decide, at each point where to go next. It has finished it's task when all parcels have been delivered.
-There’s the robot’s current location and the collection of undelivered parcels, each of which has a current location and a destination address. 




-Eloquent JS BOOK