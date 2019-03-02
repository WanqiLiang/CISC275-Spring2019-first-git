# CISC275-Spring2019-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?
 A list of dogs, 3 dogs and a comparator object for type Animal
 
3. Can you spot the comparator constructor call? Where is the class definition for the comparator?
	- The constructor call is in line 16:new Comparator<Animal>();
	- We define the class immediately in the following {}, which is
	@Override
			public int compare(Animal a, Animal b){
			    return a.getLegs() - b.getLegs();
			}