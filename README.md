# CS210 
Module 8 Assignment

Summarize the project and what problem it was solving.
  The assignment was to develop an application responsible for tracking a small grocer's produce sales throughout a given day. The program had to read through a text file that documented each sale, then sort them into lists to return a readable formatted list, a text-based histogram, or an individual item lookup. 
  
What did you do particularly well?
   This assignment required me to link python and C++ code, and read through text files. It required me to access a culmination of the topics we learned throughout the duration of CS210. I think I had a lot of room for improvement, but overall I think my code was generally clean and easy to follow. My method names were clear, supporting the program's readability. 
   
Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
  When programming, I wanted to use a method that would open/read the text file so that I would not have to open it individually for each request. I figured implementing this method would reflect foresight for the programs scalability. I ran into a couple of snags the prevented me from doing so. Ideally, I would call a method when the program was run to read the items and frequencies into a dictionary. I had trouble creating this dictionary in a global space to be accessed by future methods to output a list or histogram. 
  
Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
  The piece of code I struggled the most with was creating a global dictionary for the item frequencies in my python code. After populating the dictionary, I was unable to itterate through it in following methods, as the dictionary was appearing empty. When testing, the python code was being reinstantuated, causing it to run through an instance where the dictionary hadn't been populated to run the next method. I temporarily bypassed this by reading the dictionary in each method, though I would've like to spend more time troubleshooting the global dictionary. 
  
What skills from this project will be particularly transferable to other projects or course work?
  Linking different languages is an ineresting concept that I'm sure will be fruitful in upcoming projects. Reading files seems equally useful. I have been curious about outputting frames of visuals to create an animation that corresponds to user input. I believe understanding the aformentioned topics covered is the first step to being able to implement such a task.

How did you make this program maintainable, readable, and adaptable?
  Using clear/consistent naming conventions, inline comments, and concise methods, I believe I made this code easy to read and maintain. The method names clearly illustrate/describe the task being completed, and the variables avoid confusing shorthand. I would like to continue working on this project to provide more functionality to the user once the information is read from the text file. 
