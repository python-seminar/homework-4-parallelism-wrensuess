# homework-4-parallelism-wrensuess
homework-4-parallelism-wrensuess created by GitHub Classroom

I ran the pi approximation using the provided simple algorithm (in serial), as well as in parallel using multiprocessing and an iPython 
cluster. This was done on my 2011 MacBook Pro with 2.7 GHz Intel i7 and two cores. For arrays larger than ~10^3, the multiprocessing 
methods were more efficient than doing computation in serial; this is expected based on our lecture in class. Even for large arrays,
the multiprocessing wasn't that much faster than doing calculations in serial. I expect this is mostly because my computer only has
two cores, so the improvement in speed could only be up to a factor of two. In practice, it's less than a factor of two because of 
increased overhead when multiprocessing. The two multiprocessing methods had nearly identical efficiencies for me. I expect that this has
to do with the fact that I was running both methods with four "cores" despite the fact that I only have two cores.
