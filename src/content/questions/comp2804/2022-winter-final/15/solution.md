Here the thing is easy but tricky:

For simplicity lets take a1 a2 and a3 are our permutations of set {1,2,3}

so Pr(A=a1>a2) = 1/2 because swapping the values of the variables a1 and a2 will make the sign turn to > and violating the constraints. so we can swap in 2! ways and for all ways the signs will change except 1 way. ie : a1 > a2.

under same logic we can say for Pr(B=a2>a3) = 1/2.

Similarly for Pr(A intersect B ) = 1/3! = 1/6. because under only 1 condition a1>a2>a3 and swapping there values will lead to something else compared to the condition we want.

so we can see Pr(A intersect B) < Pr(A) * Pr(B)

what for the big numbers now ? like n = 100 or 200 instead of 3?

actually n doesnt put an affect here because permutation is something know as a unform distributions.

So irrespective of the value of n for a subset of k it will always be 1/k! as the probability to get a specific sign sequence.
