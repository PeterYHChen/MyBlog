# See you~

Time Limit: 5000/3000 MS (Java/Others) Memory Limit: 65535/32768 K (Java/Others)
Total Submission(s): 200 Accepted Submission(s): 67

### Problem Description
Now I am leaving hust acm. In the past two and half years, I learned so many knowledge about Algorithm and Programming, and I met so many good friends. I want to say sorry to Mr, Yin, I must leave now ~~>.<~~. I am very sorry, we could not advanced to the World Finals last year. 
When coming into our training room, a lot of books are in my eyes. And every time the books are moving from one place to another one. Now give you the position of the books at the early of the day. And the moving information of the books the day, your work is to tell me how many books are stayed in some rectangles. 
To make the problem easier, we divide the room into different grids and a book can only stayed in one grid. The length and the width of the room are less than 1000. I can move one book from one position to another position, take away one book from a position or bring in one book and put it on one position. 


### Input
In the first line of the input file there is an Integer T(1<=T<=10), which means the number of test cases in the input file. Then N test cases are followed. 
For each test case, in the first line there is an Integer Q(1<Q<=100,000), means the queries of the case. Then followed by Q queries. 
There are 4 kind of queries, sum, add, delete and move. 
example: 
S x1 y1 x2 y2 means you should tell me the total books of the rectangle used (x1,y1)-(x2,y2) as the diagonal, including the two points. 
A x1 y1 n1 means I put n1 books on the position (x1,y1) 
D x1 y1 n1 means I move away n1 books on the position (x1,y1), if less than n1 books at that position, move away all of them. 
M x1 y1 x2 y2 n1 means you move n1 books from (x1,y1) to (x2,y2), if less than n1 books at that position, move away all of them. 
Make sure that at first, there is one book on every grid and 0<=x1,y1,x2,y2<=1000,1<=n1<=100. 


### Output
At the beginning of each case, output "Case X:" where X is the index of the test case, then followed by the "S" queries. 
For each "S" query, just print out the total number of books in that area. 


### Sample Input
2
3
S 1 1 1 1
A 1 1 2
S 1 1 1 1
3
S 1 1 1 1
A 1 1 2
S 1 1 1 2


### Sample Output
Case 1:
1
3
Case 2:
1
4



