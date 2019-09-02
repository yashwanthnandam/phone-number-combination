# phone-number-combination
Given a string containing digits from 2-9 inclusive, return all possible letter combinations that the number could represent.

A mapping of digit to letters (just like on the telephone buttons) is given below. Note that 1 does not map to any letters.

Complexity Analysis

Time complexity : \mathcal{O}(3^N \times 4^M) where N is the number of digits in the input that maps to 3 letters (e.g. 2, 3, 4, 5, 6, 8) and M is the number of digits in the input that maps to 4 letters (e.g. 7, 9), and N+M is the total number digits in the input.

Space complexity : \mathcal{O}(3^N \times 4^M) since one has to keep 3^N \times 4^M3 solutions.
