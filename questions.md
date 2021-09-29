# HW2 Questions
## UMBC CMSC 671 fall 2021

Please answer the following questions using the git [markdown syntax](https://guides.github.com/features/mastering-markdown/).  You should view this file on your repo on GitHub after pushing it to make sure it looks the way you want.  You can also use a browser extension (like [this one](https://chrome.google.com/webstore/detail/markdown-preview-plus/febilkbfcbhebfnokafefeacimjdckgl) for Chrome) to view your local file.

### (1) Describe in words the heuristic you used for the steps cost and explain why it is admissable.

The number of steps it took to reach the goal state for example DOG -> CAT took 3 steps, which was calculated whenever state goes to one valid state in the dictionary

### (2) Describe in words the heuristic you used for the scrabble cost and explain why it is admissable.

The scrabble cost is calculated by categorizing the individual cost it takes for replacing the letter in the word and adding on to the same variable again and again until it reaches
goal state.

### (3) Describe in words the heuristic you used for the frequency cost and explain why it is admissable

The dictionary was accessed and individual frequency costs were added on to the varaiable according to the state's valid word from the dictionary.


### (4) Given an intiial word W1 and goal words W2, if there is a shortest path with N steps from W1 to W2, will there also be a shortest path of N steps from W2 to W1?  Explain why or why not.

Yes, if there are N steps for W1 to W2, then there are equal steps N for W2 to w1, because according to my algorithm valid dictionary words, 
through which the propogation takes place, remain same for either W1 to W2 or W2 to W1, so the number of steps also donot change.


### (5) Using the steps cost, what is the longest path for a pair of three- and four-letter words you can find?

Longest path for a 3 lettered word is (ask -> why) ask -> ass -> ahs -> aha -> wha -> why     steps = 5
Longest path for a 4 lettered word is (icky -> murk) inky -> inks -> inns -> ions -> mons -> mans -> mars -> mark -> murk     steps = 9

