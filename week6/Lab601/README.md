# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code
   ![570610563](http://www.mx7.com/i/dde/dbs3hs.png)
2. Detail explaination about the identified pattern and all the parcipants							
	Design Pattern : Factory Method 										
	Product : Herbivore , Carnivore											
	ConcreteProduct :  Wildebeest, Lion, Bison, Wolf 									
	Creator : ContinentFactory  												
	ConcreteCreator : AfricaFactory, AmericaFactor									    
3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
   ![570610563](http://www.mx7.com/i/9a7/20oxEy.png)
  - Test the new requirment by modifying the main function and show the result.
  ![570610563](http://www.mx7.com/i/7c6/rcv5eO.JPG)
  - Show the main function and snippet of C# code that is related to the process.                                             
      ContinentFactory asian = new AsianFactory();                                                                            
      world = new AnimalWorld(asian);                                                                                         
      world.RunFoodChain();

