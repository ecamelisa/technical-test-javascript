# JavaScript Technical Test
Solution for the JAvaScript technical test: **Find maximum number of words from given 

## Problem
given an array of sentences (paraghraps),find and the maximum number of words from any single item in the array

**Expected output:** '23'

## Solution
The function 'result(sentences)'work by:
1.Mapping each sentence to its word count using "split(' ').length'
2.Returning the maximum value using 'Math.max()'with the spread operator

'''javascript
function result(sentences) {
  return Math.max(...sentences.map(s =>s.split(' ').length));
}
'''
### How to Run
make sure Node.js is instaled,then run:

\'''bash
node solution.js
\'''
output:'23'

## Tech Stack
-JavaScript(Node.js)
