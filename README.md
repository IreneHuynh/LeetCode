# LeetCode

Here I will post some of my leetcode answer
I will post both a brute force solution and an optimal one
I will also provide my thinking process here as well and the question number
My goal is to be able to break the my thinking process in a shorter time

Notes:
  Some tips would be going through the brute force and then asking yourself how or if it is worth optimizing.
  
  Sometimes it is best to look at how we may branch to aggregate this same problem problem but small to our children nodes. Some questions may also be state machines such as the buy or sell types of problems. Others when it comes to not creating memory we want to look at the information we do not need and simply override it. 
  
  I found that solving a problem with different solutions helps to solidify questions too.

  To optimize questions we can rely on either memoization or even bfsing algorithms.
  However memoization is not always the case, we have to remember that some algorithms only go through paths once, not many times.
  
  As for brute force, we are usually maximizing or minimizing sums.
  We may even encounter cases where they ask us to build state machines.
  It is rare that we have to change the virtual indexing.
  
  I also found that when solving problems it is easier through a certain type of question. It helps for pattern recognization. For instance, I found that for arrays, there are about 3 ways to solve it. 2 pointers: where we use a swap, prefix sum: where we build an array to help us aggregate the current sums, and lastly something new. In one case, it could simply be arithmetic manipulation, another can be virtual indexing.
