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

- [X] [Sort Colors](‎https://leetcode.com/problems/sort-colors/) note: m=0

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

## In-place Reversal of a Linked List (06/15/25)

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

## Two Heaps

- [ ] [Maximize Capital](https://leetcode.com/problems/ipo/)

- [ ] [Sliding Window Median](https://leetcode.com/problems/sliding-window-median/)

- [ ] [Find Median from a Data Stream](https://leetcode.com/problems/find-median-from-data-stream/)

- [ ] [Schedule Tasks on Minimum Machines](https://leetcode.com/problems/task-scheduler/)?

## K-way merge

- [ ] [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/)

- [ ] [Kth Smallest Number in M Sorted Lists](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/)?

- [ ] [Find K Pairs with Smallest Sums](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/)

- [ ] [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/)

- [ ] [Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/)

- [ ] [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/)

## Top K Elements

- [ ] [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/)

- [ ] [Reorganize String](https://leetcode.com/problems/reorganize-string/)

- [ ] [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/)

- [ ] [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)

- [ ] [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/)

- [ ] [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)

- [ ] [Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/)

## Modified Binary Search

- [ ] [Binary Search](https://leetcode.com/problems/binary-search/)

- [ ] [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)

- [ ] [First Bad Version](https://leetcode.com/problems/first-bad-version/)

- [ ] [Random Pick with Weight](https://leetcode.com/problems/random-pick-with-weight/)

- [ ] [Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements/)

- [ ] [Single Element in a Sorted Array](https://leetcode.com/problems/single-element-in-a-sorted-array/)

- [ ] [Search in Rotated Sorted Array II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/)

## Subsets

- [ ] [Subsets](https://leetcode.com/problems/subsets/)

- [ ] [Permutations](https://leetcode.com/problems/permutations/)

- [ ] [Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)

- [ ] [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/)

- [ ] [Find K-Sum Subsets](https://leetcode.com/problems/subarray-sum-equals-k/)?

## Greedy Techniques

- [ ] [Jump Game I](https://leetcode.com/problems/jump-game/)

- [ ] [Boats to Save People](https://leetcode.com/problems/boats-to-save-people/)

- [ ] [Gas Stations](https://leetcode.com/problems/gas-station/)

- [ ] [Two City Scheduling](https://leetcode.com/problems/two-city-scheduling/)

- [ ] [Jump Game II](https://leetcode.com/problems/jump-game-ii/)

## Backtracking

- [ ] [N-Queens](https://leetcode.com/problems/n-queens/)

- [ ] [Word Search](https://leetcode.com/problems/word-search/)

- [ ] [House Robber III](https://leetcode.com/problems/house-robber-iii/)

- [ ] [Restore IP Addresses](https://leetcode.com/problems/restore-ip-addresses/)

- [ ] [Flood Fill](https://leetcode.com/problems/flood-fill/)

- [ ] [Sudoku Solver](https://leetcode.com/problems/sudoku-solver/)

- [ ] [Matchsticks to Square](https://leetcode.com/problems/matchsticks-to-square/)

## Dynamic Programming

- [ ] [0/1 Knapsack]()?

- [ ] [Coin Change](https://leetcode.com/problems/coin-change/)

- [ ] [N-th Tribonacci Number](https://leetcode.com/problems/n-th-tribonacci-number/)

- [ ] [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)

- [ ] [Counting Bits](https://leetcode.com/problems/counting-bits/)

- [ ] [01 Matrix](https://leetcode.com/problems/01-matrix/)

- [ ] [House Robber II](https://leetcode.com/problems/house-robber-ii/)

- [ ] [Word Break](https://leetcode.com/problems/word-break/)

- [ ] [Word Break II](https://leetcode.com/problems/word-break-ii/)

- [ ] [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/)

- [ ] [Combination Sum](https://leetcode.com/problems/combination-sum/)

- [ ] [Palindromic Substrings](https://leetcode.com/problems/palindromic-substrings/)

- [ ] [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/)

- [ ] [Decode Ways](https://leetcode.com/problems/decode-ways/)

- [ ] [Minimum Number of Refueling Stops](https://leetcode.com/problems/minimum-number-of-refueling-stops/)

- [ ] [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)

## Topological Sort

- [ ] [Compilation Order]()?

- [ ] [Alien Dictionary](https://leetcode.com/problems/alien-dictionary/)

- [ ] [Verifying an Alien Dictionary](https://leetcode.com/problems/verifying-an-alien-dictionary/)

- [ ] [Course Schedule II](https://leetcode.com/problems/course-schedule-ii/)

- [ ] [Course Schedule](https://leetcode.com/problems/course-schedule/)

- [ ] [Find All Possible Recipes from Given Supplies](https://leetcode.com/problems/find-all-possible-recipes-from-given-supplies/)

## Matrices

- [ ] [Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/)

- [ ] [Rotate Image](https://leetcode.com/problems/rotate-image/)

- [ ] [Spiral Matrix](https://leetcode.com/problems/spiral-matrix/)

- [ ] [Where Will the Ball Fall](https://leetcode.com/problems/where-will-the-ball-fall/)

## Graphs

- [ ] [Network Delay Time](https://leetcode.com/problems/network-delay-time/)

- [ ] [Paths in Maze That Lead to Same Room](https://leetcode.com/problems/paths-in-maze-that-lead-to-same-room/)

- [ ] [Clone Graph](https://leetcode.com/problems/clone-graph)

- [ ] [Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/)

- [ ] [Bus Routes](https://leetcode.com/problems/bus-routes/)

## Tree Depth First Search

- [ ] [Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/)

- [ ] [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/)

- [ ] [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)

- [ ] [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/)

- [ ] [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/)

- [ ] [Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree)

- [ ] [Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal)

- [ ] [Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/)

- [ ] [Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree)

- [ ] [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/description/)

- [ ] [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)

- [ ] [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst)

## Tree Breadth First Search

- [ ] [Level Order Traversal of Binary Tree](https://leetcode.com/problems/binary-tree-level-order-traversal/)

- [ ] [Binary Tree Zigzag Level Order Traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)

- [ ] [Populating Next Right Pointers in Each Node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/)

- [ ] [Vertical Order Traversal of a Binary Tree](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/)

- [ ] [Symmetric Tree](https://leetcode.com/problems/symmetric-tree)

- [ ] [Word Ladder](https://leetcode.com/problems/word-ladder)

- [ ] [Connect All Siblings of a Binary Tree](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/)

## Trie

- [ ] [Implement Trie](https://leetcode.com/problems/implement-trie-prefix-tree/)

- [ ] [Search Suggestions System](https://leetcode.com/problems/search-suggestions-system/)

- [ ] [Replace Words](https://leetcode.com/problems/replace-words/)

- [ ] [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/)

- [ ] [Word Search II](https://leetcode.com/problems/word-search-ii/)

- [ ] [Lexicographical Numbers](https://leetcode.com/problems/lexicographical-numbers/)

## Hash Maps

- [ ] [Design Hashmap](https://leetcode.com/problems/design-hashmap/)

- [ ] [Fraction to Recurring Decimal](https://leetcode.com/problems/fraction-to-recurring-decimal/)

- [ ] [Logger Rate Limiter](https://leetcode.com/problems/logger-rate-limiter/)

- [ ] [Next Greater Element](https://leetcode.com/problems/next-greater-element-i/)

- [ ] [Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/)

- [ ] [Longest Palindrome](https://leetcode.com/problems/longest-palindrome/)

## Knowing What to Track

- [ ] [Palindrome Permutation](https://leetcode.com/problems/palindrome-permutation/)

- [ ] [Valid Anagram](https://leetcode.com/problems/valid-anagram)

- [ ] [Design Tic-Tac-Toe](https://leetcode.com/problems/design-tic-tac-toe/)

- [ ] [Group Anagrams](https://leetcode.com/problems/group-anagrams/)

- [ ] [Maximum Frequency Stack](https://leetcode.com/problems/maximum-frequency-stack/)

- [ ] [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/)

- [ ] [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/)

- [ ] [Ransom Note](https://leetcode.com/problems/ransom-note/)

## Union Find

- [ ] [Redundant Connection](https://leetcode.com/problems/redundant-connection/)

- [ ] [Number of Islands](https://leetcode.com/problems/number-of-islands/)

- [ ] [Most Stones Removed with Same Row or Column](https://leetcode.com/problems/most-stones-removed-with-same-row-or-column)

- [ ] [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence)

- [ ] [Last Day Where You Can Still Cross](https://leetcode.com/problems/last-day-where-you-can-still-cross/)

- [ ] [Regions Cut by Slashes](https://leetcode.com/problems/regions-cut-by-slashes/)

- [ ] [Accounts Merge](https://leetcode.com/problems/accounts-merge)

- [ ] [Minimize Malware Spread](https://leetcode.com/problems/minimize-malware-spread/)

- [ ] [Evaluate Division](https://leetcode.com/problems/evaluate-division/)

## Custom Data Structures

- [ ] [Snapshot Array](https://leetcode.com/problems/snapshot-array/)

- [ ] [Time-Based Key-Value Store](https://leetcode.com/problems/time-based-key-value-store/)

- [ ] [Implement LRU Cache](https://leetcode.com/problems/lru-cache/)

- [ ] [Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/)

- [ ] [Min Stack](https://leetcode.com/problems/min-stack/)

- [ ] [LFU Cache](https://leetcode.com/problems/lfu-cache/)

## Bitwise Manipulation

- [ ] [Find the Difference](https://leetcode.com/problems/find-the-difference/)

- [ ] [Complement of Base 10 Number](https://leetcode.com/problems/complement-of-base-10-integer/)

- [ ] [Flipping an Image](https://leetcode.com/problems/flipping-an-image/)

- [ ] [Single Number](https://leetcode.com/problems/single-number/)

- [ ] [Two Single Numbers](https://leetcode.com/problems/single-number-iii/)

- [ ] [Reverse Bits](https://leetcode.com/problems/reverse-bits/)

## Challenge Yourself

- [ ] [Shortest Bridge](https://leetcode.com/problems/shortest-bridge/)
- [ ] [Number of Connected Components in an Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/)
- [ ] [Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/)
- [ ] [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)
- [ ] [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)
- [ ] [Two Sum](https://leetcode.com/problems/two-sum/)
- [ ] [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)
- [ ] [Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/)
- [ ] [Meeting Rooms](https://leetcode.com/problems/meeting-rooms/)
- [ ] [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/)
- [ ] [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/)
- [ ] [Sort List](https://leetcode.com/problems/sort-list/)
- [ ] [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/)
- [ ] [Container with Most Water](https://leetcode.com/problems/container-with-most-water/)
- [ ] [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/)
- [ ] [4Sum](https://leetcode.com/problems/4sum/)
- [ ] [Loud and Rich](https://leetcode.com/problems/loud-and-rich/)
- [ ] [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/)
- [ ] [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)
- [ ] [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/)
- [ ] [Majority Element](https://leetcode.com/problems/majority-element/)
- [ ] [Unique Paths](https://leetcode.com/problems/unique-paths/)
- [ ] [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/)
- [ ] [Permutations II](https://leetcode.com/problems/permutations-ii/)
- [ ] [Number of Provinces](https://leetcode.com/problems/number-of-provinces/)
- [ ] [Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/)
- [ ] [Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/)
- [ ] [Minimum Flips to Make the Binary String Alternate](https://leetcode.com/problems/minimum-number-of-flips-to-make-the-binary-string-alternating/)
- [ ] [Lemonade Change](https://leetcode.com/problems/lemonade-change/)
- [ ] [House Robber](https://leetcode.com/problems/house-robber/)
- [ ] [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/)
- [ ] [Find All Duplicates in an Array](https://leetcode.com/problems/find-all-duplicates-in-an-array/)
- [ ] [Same Tree](https://leetcode.com/problems/same-tree/)
- [ ] [Design In-Memory File System](https://leetcode.com/problems/design-in-memory-file-system/)
- [ ] [Design File System](https://leetcode.com/problems/design-file-system/)
- [ ] [Asteroid Collision](https://leetcode.com/problems/asteroid-collision/)
- [ ] [Rotting Oranges](https://leetcode.com/problems/rotting-oranges/)
- [ ] [Add Binary](https://leetcode.com/problems/add-binary/)
- [ ] [Multiply Strings](https://leetcode.com/problems/multiply-strings)



