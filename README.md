# Recursivesteps

A child is standing at the bottom of a stairway with n number of steps. He can take either 1, 2, or 3 steps at a time to reach the top. How many different combinations of steps can he take to reach the top?

This recursive solution solves the problem but very inefficiently as the solution is n-cubed. Options to reduce runtime is caching with a dictionary to eliminate repeated calculations of the same number of steps remaining. 
