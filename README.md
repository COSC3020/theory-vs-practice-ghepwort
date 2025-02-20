# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

Add your answers to this markdown file.


## Answers

### Question 1
* Asymptotic analysis can be misleading as constants are thrown out.
* Lower order terms are dropped which can make an algorithm seem faster than it is for small data sets.
* Everyone's hardware is different so results can vary from theory to practice and even from one persons machine to the next.

### Question 2
* $\frac{log_{2}(10000)}{log_{2}(1000)}\cdot5=\frac{4}{3}\cdot5=6.67$ seconds.
* I got this answer by taking the ratio between the numbers inorder to see percentage wise how much longer it should take then multiplied that by the time the 1,000 elements took to get the time for 10,000 elements. This assumes that both trees are balanced or close to balanced. 

### Question 3 
* The attempt doing 10000 could be working on multiple tasks at once such as running the program and streaming a video and running heavy software to find existance of aliens. In contrast 1000 elements could be running in isolation. The increase in tasks running while doing 10000 elements can slow down the runtime of the program. 
* The cooling system could have been entirely and savagely ripped out of the computer for the input with 10000 elements. This could have caused the system to be throttled and therefor caused a significant decrease in preformance.
* The two inputs could have been run on different machines. 1000 elements on a machine that uses top of the line parts will run a lot faster than 10000 elements on my grandma's computer that has a good chance to be older than I am.

### Credits

I used your help you gave in class on the "review day" for help understanding that I needed to be more explicit with the answers.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
