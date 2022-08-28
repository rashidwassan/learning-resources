###What is Dynamic Programming?
		Dynamic Programming is a technique in computer programming that helps to efficiently 
	solve a class of problems that have overlapping subproblems and optimal substructure property.

	If any problem can be divided into subproblems, which in turn are divided into smaller 
	subproblems, and if there are overlapping among these subproblems, then the solutions 
	to these subproblems can be saved for future reference. In this way, efficiency of the 
	CPU can be enhanced. 

		This method of solving a solution is referred to as dynamic programming. Such problems 
	involve repeatedly calculating the value of the same subproblems to find the optimum solution.

###How DP works?

	Dynamic programming works by storing the result of subproblems so that when their solutions are 
	required, they are at hand and we do not need to recalculate them.

	This technique of storing the value of subproblems is called memoization. By saving the values 
	in the array, we save time for computations of sub-problems we have already come across.



	Dynamic programming by memoization is a top-down approach to dynamic programming. By reversing 
	the direction in which the algorithm works i.e. by starting from the base case and working 
	towards the solution, we can also implement dynamic programming in a bottom-up manner.