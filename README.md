# Service-Lane
You will be given an array of widths at points along the road (indices), then a list of the indices of entry and exit points. Considering each entry and exit point pair, calculate the maximum size vehicle that can travel that segment of the service lane safely.

Function Description

Complete the serviceLane function in the editor below. It should return an array of integers representing the maximum width vehicle that can pass through each segment of the highway described.

serviceLane has the following parameter(s):

n: an integer denoting the size of the casses array
cases: a two dimensional array of integers where each element is an array of two integers representing starting and ending indices for a segment to consider .

Output Format

For each test case, print the number that represents the largest vehicle type that can pass through the entire segment of the service lane between indexes i and j inclusive.

Sample Input

8 5
2 3 1 2 3 2 3 3
0 3
4 6
6 7
3 5
0 7
Sample Output

1
2
3
2
1
Explanation

Below is the representation of the lane:

   |HIGHWAY|Lane|    ->    Width

0: |       |--|            2
1: |       |---|           3
2: |       |-|             1
3: |       |--|            2
4: |       |---|           3
5: |       |--|            2
6: |       |---|           3
7: |       |---|           3

HackerRank: https://www.hackerrank.com/challenges/service-lane/problem
