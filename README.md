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
* Lower order terms are dropped which can make an algorithm seem faster (or slower) than it is.
* Everyone's hardware is different so results can vary from theory to practice and even from one persons machine to the next.

### Question 2
* $\frac{log_{2}(10000)}{log_{2}(1000)}\cdot5=\frac{4}{3}\cdot5=6.67$ seconds.

### Question 3
* If you have an unbalanced tree then the tree may act more like a linked list and has to search every element which is time intensive.
* While the tree's search method may work, it may be poorly implemented which may make it take longer to search.
* If the machine is working on multiple tasks at once (ie. running the program and streaming a video and running heavy software) it can slow down the runtime of the program.


### Credits
I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.