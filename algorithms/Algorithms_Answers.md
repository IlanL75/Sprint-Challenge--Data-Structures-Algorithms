Add your answers to the Algorithms exercises here.

I:

a. O(n)

b. O(n^4)

c. O(n)


II:

We need to start checking from the lowest floor, since in opposite case we 
will broke every egg until we find f-floor. 
Dropp egg and increase n by one until egg is broken,
then return n-1, since this is last floor where egg is not broken.
