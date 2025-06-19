## Warmup (06/02/25)

- [X] [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)

- [X] [Check if the Sentence Is Pangram](https://leetcode.com/problems/check-if-the-sentence-is-pangram/)

- [X] [Reverse Vowels of a String](https://leetcode.com/problems/reverse-vowels-of-a-string/) note: python strings are immutable (leads to o(n^2) time). can use res = [] then .join() or two pointers instead
      
- [X] [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/)
      
- [X] [Valid Anagram](https://leetcode.com/problems/valid-anagram/)
      
- [X] [Shortest Word Distance](https://leetcode.com/problems/shortest-word-distance/) note: use two indices for word1/2, then abs()
      
- [X] [Number of Good Pairs](https://leetcode.com/problems/shortest-word-distance/) note: hashmap for char count
      
- [X] [Sqrt(x)](https://leetcode.com/problems/sqrtx/) note: o(logx) soln, think bin search ending case and what to return (l, m, r)

## Two Pointers (06/06/25)

- [X] [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)
      
- [X] [Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/) note: use a deque
      
- [X] [3Sum](https://leetcode.com/problems/3sum/) 

- [X] [3Sum Closest](https://leetcode.com/problems/3sum-closest/) note: update res and move pointers separately

- [X] [3Sum Smaller](https://leetcode.com/problems/3sum-smaller/) note: think abt how to update res
      
- [X] [Sort Colors](https://leetcode.com/problems/sort-colors/) note: m = 0

- [X] [4Sum](https://leetcode.com/problems/4sum/)

- [X] [Backspace String Compare](https://leetcode.com/problems/backspace-string-compare/)

- [X] [Shortest Unsorted Continuous Subarray](https://leetcode.com/problems/shortest-unsorted-continuous-subarray/) note: move inwards, deal with min/max vals, move outwards

## Fast and Slow Pointers (06/06/25)

- [X] [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)

- [X] [Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/)

- [X] [Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/) note: parallel move to find cycle start

- [X] [Happy Number](https://leetcode.com/problems/happy-number/) note: helper, check meeting point=1

- [X] [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/) note: middle, reverse, step

- [X] [Reorder List](https://leetcode.com/problems/reorder-list/) note: middle, reverse, merge

- [X] [Circular Array Loop](https://leetcode.com/problems/circular-array-loop/) note: use % for circularity, check directions, mark path as visited

## Sliding Window (06/07/25)

- [X] [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/)

- [X] [Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/)

- [X] [Longest Substring with At Most K Distinct Characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/)

- [X] [Fruits Into Baskets](https://leetcode.com/problems/fruit-into-baskets/)

- [X] [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/)

- [X] [Max Consecutive Ones III](https://leetcode.com/problems/max-consecutive-ones-iii/)

- [X] [Permutation in String](https://leetcode.com/problems/permutation-in-string/)

- [X] [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/)
      
- [X] [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) note: need vs have

- [X] [Substring with Concatentation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) note: track word count with word_len offset

- [X] [Subarray Product Less Than K](https://leetcode.com/problems/subarray-product-less-than-k/) note: add check for k<=1 

## Merge Intervals (06/07/25)

- [X] [Merge Intervals](https://leetcode.com/problems/merge-intervals/)

- [X] [Insert Interval](https://leetcode.com/problems/insert-interval/) note: for loops don't work

- [X] [Interval List Intersections](https://leetcode.com/problems/interval-list-intersections/) note: only add to res if start<=end

- [X] [Meeting Rooms](https://leetcode.com/problems/meeting-rooms/)

- [X] [Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/) note: heap soln is straightforward

- [X] [Task Scheduler](https://leetcode.com/problems/task-scheduler/) note: count max freq, calculate min time, take max of min time and tasks
      
- [X] [Employee Free Time](https://leetcode.com/problems/employee-free-time/) note: merge intervals, find the gaps

## Cyclic Sort (06/08/25)

- [X] [Missing Number](https://leetcode.com/problems/missing-number/) note: xor, gauss solns
      
- [X] [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/)

- [X] [Find The Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/) note: floyds cycle detection

- [X] [Find All Duplicates in an Array](https://leetcode.com/problems/find-all-duplicates-in-an-array/)

- [X] [Set Mismatch](https://leetcode.com/problems/set-mismatch/)

- [X] [First Missing Positive](https://leetcode.com/problems/first-missing-positive/) 

- [X] [Find the First K Missing Positive Numbers](https://leetcode.com/problems/kth-missing-positive-number/)

## In-place Reversal of a Linked List (06/14/25)

- [X] [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) note: try to visualize

- [X] [Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/) note: head insertion

- [X] [Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/) note: get_kth(), then reverse normally, reconnect group
      
- [X] [Rotate List](https://leetcode.com/problems/rotate-list/) note: base case, check length, make circular, calculate new tail, break circular

## Stacks (06/14/25)

- [X] [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)

- [X] [Reverse String](https://leetcode.com/problems/reverse-string/)

- [X] [Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/) note: use hashmap to store next greater element of nums2, then fill with -1s

- [X] [Sort an Array](https://leetcode.com/problems/sort-an-array/)

- [X] [Simplify Path](https://leetcode.com/problems/simplify-path/) note: meta xd

## Monotonic Stacks (06/15/25)

- [X] [Remove Nodes From Linked List](https://leetcode.com/problems/remove-nodes-from-linked-list/) note: recreate linked list

- [X] [Remove All Adjacent Duplicates In String](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/)

- [X] [Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/)

- [X] [Daily Temperatures](https://leetcode.com/problems/daily-temperatures/) note: have separate res, stack arrays

- [X] [Remove All Adjacent Duplicates in String II](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string-ii/) note: store [ch, count] in stack

- [X] [Sum of Subarray Minimums](https://leetcode.com/problems/sum-of-subarray-minimums/) note: get ple, nle for each element then do arr * ple * nle

- [X] [Remove K Digits](https://leetcode.com/problems/remove-k-digits/) note: pop remaining k after iterating, strip leading 0s

## Hash Maps (06/16/2025)

- [X] [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/)

- [X] [Largest Unique Number](https://leetcode.com/problems/largest-unique-number/)

- [X] [Maximum Number of Balloons](https://leetcode.com/problems/maximum-number-of-balloons/)

- [X] [Longest Palindrome](https://leetcode.com/problems/longest-palindrome/) note: count # of odd char freqs

- [X] [Ransom Note](https://leetcode.com/problems/ransom-note/)

## Level Order Traversal Pattern (06/16/25)

- [X] [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) note: standard bfs

- [X] [Binary Tree Level Order Traversal II](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/)

- [X] [Find Largest Value in Each Tree Row](https://leetcode.com/problems/find-largest-value-in-each-tree-row/)

- [X] [Maximum Width of Binary Tree](https://leetcode.com/problems/maximum-width-of-binary-tree/) note: normalize index,  res=max(res,i+1)

- [X] [Maximum Level Sum of a Binary Tree](https://leetcode.com/problems/maximum-level-sum-of-a-binary-tree/)

- [X] [Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) note: use zigzag=1 or -1

- [X] [Even Odd Tree](https://leetcode.com/problems/even-odd-tree/)

- [X] [N-ary Tree Level Order Traversal](https://leetcode.com/problems/n-ary-tree-level-order-traversal/)

## Tree Breadth First Search (06/17/25)

- [X] [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)

- [X] [Binary Tree Level Order Traversal II](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/)

- [X] [Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)

- [X] [Averages of Levels in Binary Tree](https://leetcode.com/problems/average-of-levels-in-binary-tree/)

- [X] [Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/)

- [X] [Populating Next Right Pointers in Each Node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/) note: use .next to traverse levels

- [X] [Populating Next Right Pointers in Each Node II](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/) note: o(1) space soln

- [X] [Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/)

## Tree Depth First Search

- [X] [Path Sum](https://leetcode.com/problems/path-sum/)

- [X] [Path Sum II](https://leetcode.com/problems/path-sum-ii/) note: keep track of path, append its deep copy, involves backtracking

- [ ] [Sum Root to Leaf Numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/)

- [ ] [Check If a String Is a Valid Sequence from Root to Leaves Path in a Binary Tree](https://leetcode.com/problems/check-if-a-string-is-a-valid-sequence-from-root-to-leaves-path-in-a-binary-tree/)

- [ ] [Path Sum III](https://leetcode.com/problems/path-sum-iii/)
      
- [ ] [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/)

- [ ] [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/)

## Graphs

## Island (Matrix Traversal)

## Two Heaps

## Subsets

## Modified Binary Search

## Bitwise XOR

## Top 'K' Elements

## K-way Merge

## Greedy Algorithms

## 0/1 Knapsack (Dynamic Programming)

## Backtracking

## Trie

## Topological Sort (Graph)

## Union Find

## Ordered Set

## Prefix Sum

## Multi-threaded

## Miscellaneous

## Easy

## Medium

## Hard
