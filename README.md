Technojam_Tasks_DSA

1) Power of 2 - Algorithm- Brute Force Approach - (  running a loop from 2^0 to 2^30 and comparing it with the number ). Time Complexity O(n).
![Screenshot (12)](https://user-images.githubusercontent.com/113130698/201444667-835f1d2f-7184-400b-b90b-17e048a3dfcb.png)
![Screenshot (13)](https://user-images.githubusercontent.com/113130698/201444686-a7797064-107d-4494-8542-03e36d6216f9.png)

2)Negative-Positive Existential Crisis- Brute force Approach

Algorithm
 a) sorting the array

 b)Starting the first loop from the largest number in reverse order and comparing its negative with the rest of the array.If negative of the number is equal to the number then the number is returned from the function . If no such number exists whose negative exists in the sorted array then -1 is returned from the function.
 ![Screenshot (16)](https://user-images.githubusercontent.com/113130698/201445577-c4072770-3d38-4d19-8711-b0424abaee33.png)
![Screenshot (17)](https://user-images.githubusercontent.com/113130698/201445580-8a661110-2d03-467a-8cc5-8b663166c4b2.png)

Time complexity - o(n^2)

We can reduce the time complexity by using the binary search function to O(n logn).
![Screenshot (19)](https://user-images.githubusercontent.com/113130698/201445781-93bda910-39bd-4398-abc3-6f556278da75.png)
![Screenshot (18)](https://user-images.githubusercontent.com/113130698/201445814-73a6ae68-5547-4de6-ba64-e1a0c8635162.png)

3)Are there common factors? - Using Brute Force Approach. Time complexity - O(n).

Algorithm - a) running a loop from 1 to minima of two numbers. Counting their common factors by using mod function.( if a%n=0 it means n is factor of a).

b) Counting the common factors in the loop.

 c) Returning common factors from the function.

 ![Screenshot (36)](https://user-images.githubusercontent.com/113130698/201446722-313a3f5f-643e-4fdc-affd-582c78b56950.png)
![Screenshot (37)](https://user-images.githubusercontent.com/113130698/201446726-1c929b37-6959-4673-8856-786c86dbec9b.png)

4)69-Problems - Brute Force Approach . Time complexity- O(n) .
Algorithm - a) finding the index of 6 using while loop.

b) using basic maths to replace 6 with 9 and returning the possible largest number.

![Screenshot (23)](https://user-images.githubusercontent.com/113130698/201447418-7d7ba72a-f61d-444d-90d2-9a5845bfff1b.png)
![Screenshot (24)](https://user-images.githubusercontent.com/113130698/201447424-4847384b-e55d-4425-8cb5-69a404eef3a5.png)

5)Problem number 5 - Creating a function Possiblecuts to cut the array according to the given problem.
![Screenshot (29)](https://user-images.githubusercontent.com/113130698/201447622-32c87716-aa4c-4abe-b3d2-a1a9a8d69813.png)
 Brute Force Approach . Time Complexity - O(n).
 Algorithm -

  a) Running a loop and comparing one number of the array to the next one( considering array is sorted)
  
  b) Checking if sum of two consecutive numbers in an array is greater than or equal to k.

  c) counting all the possiblecuts in the loop .

  d) Returning the count to the main function.

  Checking Outputs 

  ![Screenshot (29)](https://user-images.githubusercontent.com/113130698/201447622-32c87716-aa4c-4abe-b3d2-a1a9a8d69813.png)
  ![Screenshot (30)](https://user-images.githubusercontent.com/113130698/201447654-bc506c0f-e213-4bfb-949b-a3fd7d4a586f.png)

Medium Problems
1)Subarray with max bitwise - Time Complexity is 0 (n).
Algorithm - Using a simple concept that Maximium And Bitwise between two numbers is when two numbers are equal.
for example first case 4&4 = 4 and in second case 4&2 =0. 

a) Finding out the maximium number in the array.

b) Running a loop ( traversing throught the array) and checking if another maximium no exists.Counting all the maximium numbers(if exists).
c) Returning the count from the function if more than one maximium number exists. Else returning 1 which is the count of maximium number.
![Screenshot (34)](https://user-images.githubusercontent.com/113130698/201448866-7e3aaf5b-fe0f-4585-bf17-26ffe2412f78.png)
![Screenshot (35)](https://user-images.githubusercontent.com/113130698/201448874-ce9de756-c659-4603-a5c3-ff55e0787df6.png)
 
