# DS Algo Tracker

A repo to track my progress in Data Structures and Algorithms. 

| Questions | Tip | Difficulty | Time Complexity | Space Complexity |
| --------------- | --------------- | --------------- |--------------- |--------------- |
| 1.    Two Number Sum: https://www.algoexpert.io/questions/Two%20Number%20Sum | use Hashmap for O(n) | Easy | | |
| 2.    Validate Subsequence: https://www.algoexpert.io/questions/Validate%20Subsequence| can be done without a flag, cleaner code | Easy | | |
| 3.    Sorted Squared Array: https://www.algoexpert.io/questions/Sorted%20Squared%20Array| Two pointers, one for max, one for min. Whenver it is mentioned that the input is in a specific order, that usually hints you that there is a more optimal sol than the brute force one. mostly a linear time complexity is available | Easy | | |
| 4.    Tournament Winner: https://www.algoexpert.io/questions/Sorted%20Squared%20Array| Object.keys, Object.values | Easy | | |
| 5.    Non Constructible change: https://www.algoexpert.io/questions/Non-Constructible%20Change| next number to be added (n) > change+1, then new change = change + n, if change = k, then we make change from 1 to K| Easy, tricky | | |
| 6.    Closest Value in BST: https://www.algoexpert.io/questions/Find%20Closest%20Value%20In%20BST| simple traversal, avg time(Balanced BST) - O(logN), worst case - O(N)(One branch tree, so we are not eliminating half the BST in each step). If done recursively space- O(N), iteratively - O(1)| Easy | | |
| 7.    Branch Sums: https://www.algoexpert.io/questions/Branch%20Sums| simple traversal | Easy | | |
| 8.    Node Depths : https://www.algoexpert.io/questions/Node%20Depths| recursive is intuitive, take a look at iterative approach using stack | Easy | | |
| 9.    Depth first search : https://www.algoexpert.io/questions/Depth-first%20Search | Understand that time complexity is O(V+E), because- sum(pushing the vertex to array)= V, sum(traversing the neibhour of each node) = E | Easy | | |
| 10.   Minimum waiting Time : https://www.algoexpert.io/questions/Minimum%20Waiting%20Time | Understand that time complexity is O(V+E), because- sum(pushing the vertex to array)= V, sum(traversing the neibhour of each node) = E | Easy | | |
| 11.   Class Photos : https://www.algoexpert.io/questions/Class%20Photos |  | Easy | | |
| 12.   Tandem Cycle : https://www.algoexpert.io/questions/Tandem%20Bicycle |  | Easy | | |
| 13.   Remove Duplicates from Linked List : https://www.algoexpert.io/questions/Remove%20Duplicates%20From%20Linked%20List |  | Easy | | |
| 14.   Nth Fibonacci : https://www.algoexpert.io/questions/Remove%20Duplicates%20From%20Linked%20List | in the memoization solution, if i put: If(memo(n)) instead of if(n in memo)  | Easy | | |
| 15.   Product Sum : https://www.algoexpert.io/questions/Product%20Sum |  | Easy | | |
| 16.   Binary Search : https://www.algoexpert.io/questions/Binary%20Search | Iterative is better for space | Easy | | |
| 17.   Find three largest nos : https://www.algoexpert.io/questions/Find%20Three%20Largest%20Numbers |  | Easy | | |
| 18.   Bubble Sort : https://www.algoexpert.io/questions/Bubble%20Sort | Avg and worst case time complexity : O(N^2), best case scenario is when we are given a sorted array-Time complexity : O(N) , need to use a flag to get best case time complexity | Easy | | |
| 19.   Insertion Sort : https://www.algoexpert.io/questions/Insertion%20Sort | Avg and worst case time complexity : O(N^2), best case scenario is when we are given a sorted array-Time complexity : O(N) , need to use a flag to get best case time complexity | Easy | Avg and Worst case- O(N^2), best case scenario when  given a sorted array-O(N) | O(1) |
| 20.   Selection Sort : https://www.algoexpert.io/questions/Selection%20Sort |  | Easy | Best, Avg and Worst case- O(N^2) | O(1) |
| 21.   Palindrome check : https://www.algoexpert.io/questions/Palindrome%20Check | Although not optimal, the recursive method is interesting(Solution 3) | Easy | O(N) | O(1) |
| 22.   Caesar Cipher Encryptor  :https://www.algoexpert.io/questions/Caesar%20Cipher%20Encryptor | use of Modulus is interesting, check out the use case | Easy | O(N) | O(N) |
| 23.   Run Length Encoding  :https://www.algoexpert.io/questions/Run-Length%20Encoding |Two catches here 1.If i use a string inside the loop to calculate the output at each step, that would be a o(N^2) operation since string concatnation is a O(N+M) operation 2.In the interview they may not explicity say to split 13 - 9 and 4, but that's what we'll have to do, since it has to be a unique mapping | Easy | O(N) | O(N), since here worst case scenario for space is 2N, when input is like ABCD |
| 24.   Generate Document  :https://www.algoexpert.io/questions/Generate%20Document | The way they do Sol 3 is more neat than mine, without using two hash tables, they use only one hash table | Easy | O(N+M) | O(c), c- no of unique character in the characters string |
| 25.   First Non Repeating Character  :https://www.algoexpert.io/questions/First%20Non-Repeating%20Character| for the optimal solution, space comple- O(1), b/c in worst case scenario, it would be O(26)(26 lowercase letters in alphabets) = O(1) | Easy | O(N) | O(1) |
| 26.   Three Number Sum :https://www.algoexpert.io/questions/Three%20Number%20Sum | the two pointer methodology is quite neat, optimal sol. | Medium | O(N^2) | O(N), because in wors case scenario all elements could be part of triplet |
| 27.   Smallest difference :https://www.algoexpert.io/questions/Smallest%20Difference | the optimal solution is neat | Medium | O(NlogN + MlogM) | O(1) |
| 28.   Move Element to End :https://www.algoexpert.io/questions/Move%20Element%20To%20End | two pointers | Easy | O(N) | O(1) |
| 29.   Monotonic Array :https://www.algoexpert.io/questions/Monotonic%20Array |  | Easy | O(N) | O(1) |
| 30.   Spiral Traverse :https://www.algoexpert.io/questions/Spiral%20Traverse | traversing the paramenter of the rectangle, and then shrinking the rectangle. See the edge case where there is a single row/coloum in the last spiral, test case 8&9| Medium | O(N) | O(1) |
| 31.   Longest Peak :https://www.algoexpert.io/questions/Longest%20Peak | Optimal sol is neat, checkout | Medium | O(N) | O(1) |
| 32.   Array of Products :https://www.algoexpert.io/questions/Array%20Of%20Products| The optimal sol with two arrays is nice, but we can solve it with flag like i did but it's too verbose | Easy | O(N) | O(N) |
| 33.   First Duplicate Value :https://www.algoexpert.io/questions/First%20Duplicate%20Value | The optimal sol is clever | Medium | O(N) | O(1) |
| 34.   Merge Overlapping Values :https://www.algoexpert.io/questions/Merge%20Overlapping%20Intervals |  | Medium | O(NlogN) | O(N)  |
| 35.   BST Construction :https://www.algoexpert.io/questions/BST%20Construction |  | Medium | Avg O(logN) Worst O(N) | Avg O(1) Worst O(N) |
| 36.   Validate BST : https://www.algoexpert.io/questions/Validate%20BST |  | Medium | O(N) | O(d) d-depth of the BST, largest branch of the BST |
| 36.   BST Traversal : https://www.algoexpert.io/questions/BST%20Traversal |  | Medium | O(N) | O(N), because we are storing the array, if we were just printing the values, then O(d) d- depth of the BST |

