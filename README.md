
There are N balls positioned in a row. Each of them is either red or white. In one move we can swap two adjacent balls. We want to arrange all the red balls into a consistent segment. What is the minimum number of swaps needed?

Write a function:

class Solution { public int solution (String S); }

that, given string S of length N built from characters "R" and "W", representing red and white balls respectively, returns the minimum number of swaps needed to arrange all the red balls into a consistent segment. If the result exceeds 109, return -1.

Examples:

1. Given S = "WRRWWR", your function should return 2. We can move the last ball two positions to the left:

"WRRWRW"

"WRRRWW"

2. Given S = "WWRWWWRWR", your function should return 4. We can move first and last red ball towards the middle one:

• "WWWRWWRWR"
• "WWWWRWRWR"
• "WWWWWRRWR"
 "WWWWWRRRW"

3. Given S = "WWW", your function should return 0. There are no red balls to arrange into a segment.

4. Given S is "RW" repeated 100,000 times, your function should return-1. The minimum needed number of swaps is greater than 109.

Write an efficient algorithm for the following assumptions:

N is an integer within the range [1..200,000];

• string S is made only of the characters 'R' and/or 'W'.

Copyright 2009-2025 by Codility Limited. All Rights Reserved. Unauthorized copying. publication or disclosure prohibited
