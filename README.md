## pears-dht

### TODO

1. Implementation for the client to register itself once a new
   installation is made
2. Create a hashinfo for each of the node corresponding to its vector
   distance array
3. Proper DHT implementation
4. Implementation to update the routing table as soon as the IP or the
   vector representation changes

we have to generate a node ID corresponding to the vector distance
array. This shall be a 160-bit value. We have to generate an infohash
out of each of the search query when entered, which should also be a
160-bit value. These will be matched at the searching stage to find the
best pears


For each node, we need a routing table. It can have 8 entries. The range
of the entire
