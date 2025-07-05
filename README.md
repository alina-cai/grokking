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

## Tree Depth First Search (06/21/25)

- [X] [Path Sum](https://leetcode.com/problems/path-sum/)

- [X] [Path Sum II](https://leetcode.com/problems/path-sum-ii/) note: keep track of path, append its deep copy, involves backtracking

- [X] [Sum Root to Leaf Numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/) note: cur=cur*10+node.val

- [X] [Check If a String Is a Valid Sequence from Root to Leaves Path in a Binary Tree](https://leetcode.com/problems/check-if-a-string-is-a-valid-sequence-from-root-to-leaves-path-in-a-binary-tree/) note: track index rather than path

- [X] [Path Sum III](https://leetcode.com/problems/path-sum-iii/) note: use prefix sums, cur-targetSum
      
- [X] [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/) note: res=max(res,l+r) \n return 1 + max(l,r)

- [X] [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) note: res=max(res,node.val+l+r)

## Graphs (06/23/25)

- [X] [Find if Path Exists in Graph](https://leetcode.com/problems/find-if-path-exists-in-graph/) note: use visited set, standard dfs
      
- [X] [Number of Provinces](https://leetcode.com/problems/number-of-provinces/) note: rmbr that a node is always connected w itself, use dfs on indices

- [X] [Find Eventual Safe States](https://leetcode.com/problems/find-eventual-safe-states/) note: coloring soln to detect cycles, state=[] and mark as unvisited/visited/safe

- [X] [Minimum Number of Vertices to Reach All Nodes](https://leetcode.com/problems/minimum-number-of-vertices-to-reach-all-nodes/) note: find all indegree=0

- [X] [Bus Routes](https://leetcode.com/problems/bus-routes/) note: use stops as nodes, do bfs from start stop, explore one route and find connected routes

## Island (Matrix Traversal) (06/24/25)

- [X] [Number of Islands](https://leetcode.com/problems/number-of-islands/) note: space complexity is o(m*n) cus of recursion depth!!

- [X] [Max Area of Island](https://leetcode.com/problems/max-area-of-island/) note: just return 1+dfs()*4
      
- [X] [Flood Fill](https://leetcode.com/problems/flood-fill/) 

- [X] [Number of Closed Islands](https://leetcode.com/problems/number-of-closed-islands/) note: store each dfs call then aggregate

- [X] [Island Perimeter](https://leetcode.com/problems/island-perimeter/) note: land cells have 4 edges, -2 if neighboring land exists

- [X] [Number of Distinct Islands](https://leetcode.com/problems/number-of-distinct-islands/) note: keep shapes set, backtrack with direction (D/U/L/R)

- [X] [Detect Cycles in 2D Grid](https://leetcode.com/problems/detect-cycles-in-2d-grid/) note: keep track of parent row/col

## Two Heaps (06/25/25)

- [X] [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/) note: all nums in max_heap <= all nums in min_heap

- [X] [Sliding Window Median](https://leetcode.com/problems/sliding-window-median/) note: https://leetcode.com/problems/sliding-window-median/solutions/394302/python-clean-solution-easy-to-understand/ REVIEW!!! use delayed to_remove

- [X] [IPO](https://leetcode.com/problems/ipo/) note: greedy, use one heap per capital and profits

- [X] [Find Right Interval](https://leetcode.com/problems/find-right-interval/) note: binary search start times

## Subsets (06/26/25)

- [X] [Subsets](https://leetcode.com/problems/subsets/)

- [X] [Subsets II](https://leetcode.com/problems/subsets-ii/)

- [X] [Permutations](https://leetcode.com/problems/permutations/) note: only need backtrack(cur)

- [X] [Letter Case Permutation](https://leetcode.com/problems/letter-case-permutation/) note: backtrack cases by alpha vs num

- [X] [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) note: opened<n, then closed<opened

- [X] [Generalized Abbreviation](https://leetcode.com/problems/generalized-abbreviation/) note: either add abbreviation count or add char

- [X] [Different Ways to Add Parentheses](https://leetcode.com/problems/different-ways-to-add-parentheses/) note: divide and conquer w memoization

- [X] [Unique Binary Search Trees](https://leetcode.com/problems/unique-binary-search-trees/) note: bottom up dp

- [X] [Unique Binary Search Trees II](https://leetcode.com/problems/unique-binary-search-trees/) note: recursively generate left and right subtrees, use @lru_cache(None)

## Modified Binary Search (06/28/25)

- [X] [Binary Search](https://leetcode.com/problems/binary-search/)
      
- [X] [Search Insert Position](https://leetcode.com/problems/search-insert-position/)

- [X] [Find Smallest Letter Greater Than Target](https://leetcode.com/problems/find-smallest-letter-greater-than-target/)

- [X] [Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) note: do two searches

- [X] [Search in a Sorted Array of Unknown Size](https://leetcode.com/problems/search-in-a-sorted-array-of-unknown-size/) note: manually increment r ptr first

- [X] [Minimum Absolute Difference](https://leetcode.com/problems/minimum-absolute-difference/) note: sort first, then simulation

- [X] [Peak Index in a Mountain Array](https://leetcode.com/problems/peak-index-in-a-mountain-array/) note: uber xd

- [X] [Find in Mountain Array](https://leetcode.com/problems/find-in-mountain-array/) note: triple bin search, careful with third since its reversed

- [X] [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) note: if nums[l]<=nums[m] then check if target is between them

- [X] [Check if Array Is Sorted and Rotated](https://leetcode.com/problems/check-if-array-is-sorted-and-rotated/) note: check for wraparound too

- [X] [Rotate Array](https://leetcode.com/problems/rotate-array/) note: reverse entire arr, up to k, then from k to end

## Bitwise XOR (06/28/25)

- [X] [Single Number](https://leetcode.com/problems/single-number/) note: a^0=a, a^a=0

- [X] [Single Number III](https://leetcode.com/problems/single-number-iii/) note: xor, isolate rightmost bit, then partition

- [X] [Complement of Base 10 Integer](https://leetcode.com/problems/complement-of-base-10-integer/) note: o(logn) soln more intuitive ngl, but o(1) is just brute force flip then shift

- [X] [Flipping an Image](https://leetcode.com/problems/flipping-an-image/) note: to flip do 1-x

## Top 'K' Elements (06/30/25)

- [X] [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)

- [X] [Top K Frequent Words](https://leetcode.com/problems/top-k-frequent-words/)

- [X] [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) note: heap or quickselect

- [X] [K Closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/)

- [X] [Minimum Cost to Connect Sticks](https://leetcode.com/problems/minimum-cost-to-connect-sticks/)

- [X] [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/)

- [X] [Find K Closest Elements](https://leetcode.com/problems/find-k-closest-elements/) note: bin search on k length window

- [X] [Least Number of Unique Integers after K Removals](https://leetcode.com/problems/least-number-of-unique-integers-after-k-removals/) note: sort freqs, then greedy

- [X] [Reorganize String](https://leetcode.com/problems/reorganize-string/) note: max heap greedy

- [X] [Rearrange String k Distance Apart](https://leetcode.com/problems/rearrange-string-k-distance-apart/) note: keep track of chars in cd w a deque

- [X] [Task Scheduler](https://leetcode.com/problems/task-scheduler/) note: math or do max greedy heap

- [X] [Maximum Frequency Stack](https://leetcode.com/problems/maximum-frequency-stack/) note: initialize freq, freq_group, max_freq

## K-way Merge (07/01/25)

- [X] [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)

- [X] [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) note: while len(lists)>1: merged=[]

- [X] [Kth Smallest Element in a Sorted Matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) note: bin search w helper function count_leq()

- [X] [Smallest Range Covering Elements from K Lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) note: track min val of each row + max of nums using priority q + sliding window

- [X] [Find K Pairs with Smallest Sums](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/) : o(min(k,n)logk) soln, use heap with (total,i,j)

## Greedy Algorithms (07/01/25)

- [X] [Valid Palindrome II](https://leetcode.com/problems/valid-palindrome-ii/) note: def isPalindrome(l,r)

- [X] [Maximum Length of Pair Chain](https://leetcode.com/problems/maximum-length-of-pair-chain/) note: sort pairs by end

- [X] [Minimum Add to Make Parentheses Valid](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid/) note: no need for stack tbh

- [X] [Remove Duplicate Letters](https://leetcode.com/problems/remove-duplicate-letters/) note: make last_occurence map, use stack to keep min char that is not last occurence

- [X] [Largest Palindromic Number](https://leetcode.com/problems/largest-palindromic-number/) note: build first half with even count then mid then reverse first half

- [X] [Removing Minimum and Maximum From Array](https://leetcode.com/problems/removing-minimum-and-maximum-from-array/) note: calculate left, right, both

## 0/1 Knapsack (Dynamic Programming) (07/04/25)

- [X] [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) note: bottom up, try to find partition that equals sum(nums)//2

- [X] [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) note: prefix sums + hashmap

- [X] [Closest Subsequence Sum](https://leetcode.com/problems/closest-subsequence-sum/) note: meet in the middle, binary search latter half

- [X] [Partition Array Into Two Arrays to Minimize Sum Difference](https://leetcode.com/problems/partition-array-into-two-arrays-to-minimize-sum-difference/) note: meet in the middle, target sum=total sum//2-left subset sum

- [X] [Target Sum](https://leetcode.com/problems/target-sum/) note: bottom up, target=(total+target)/2

## Fibonacci Numbers (Dynamic Programming) (07/04/25)

- [X] [Fibonacci Number](https://leetcode.com/problems/fibonacci-number/)

- [X] [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)

- [X] [Jump Game II](https://leetcode.com/problems/jump-game-ii/) note: greedy? update farthest idx to jump to every iteration, increment res if it's the last possible jump

- [X] [Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/) note: think abt how to calculate dp

- [X] [House Robber](https://leetcode.com/problems/house-robber/)

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
