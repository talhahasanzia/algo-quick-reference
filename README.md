# algo-quick-reference
Quick reference of algos by Copilot (Claude 3.5)


## 1. Two Pointers
**Description:**
- Use two pointers to traverse array/string, usually moving toward each other or in same direction
- Often used to find pairs or subarrays that meet certain conditions

**When to Use:**
- Questions about pairs in sorted array
- Array/string problems requiring comparison of elements from both ends
- Finding triplets, subarrays with conditions

**Key Identifiers in Questions:**
- "Find pair of elements..."
- "Find triplet that sums to..."
- Palindrome problems
- Sorted array mentioned
- "Container with most water"

**Example Problems:**
- Two sum in sorted array
- Three sum
- Container with most water
- Remove duplicates
- Palindrome verification

## 2. Sliding Window
**Description:**
- Maintain a "window" that slides over array/string
- Track window state (sum, max, min, etc.)
- Expand/contract window based on conditions

**When to Use:**
- Finding subarrays/substrings with certain properties
- Calculating continuous sequence properties
- Fixed-size window problems

**Key Identifiers:**
- "Find longest substring..."
- "Find shortest subarray..."
- "Maximum/Minimum sum of k elements"
- "Continuous sequence"
- Words like "consecutive" or "contiguous"

**Example Problems:**
- Max sum subarray of size k
- Longest substring with k distinct characters
- Minimum window substring
- Maximum sum of any contiguous subarray

## 3. Fast and Slow Pointers (Floyd's Cycle)
**Description:**
- Two pointers moving at different speeds
- Used primarily for cycle detection
- Also for finding middle elements

**When to Use:**
- Linked List cycle problems
- Finding middle of linked list
- Array cycle detection

**Key Identifiers:**
- "Detect cycle..."
- "Find middle element..."
- "Circular array..."
- "Happy number"

**Example Problems:**
- Linked List cycle detection
- Find cycle start node
- Middle of linked list
- Happy number problem

## 4. Merge Intervals
**Description:**
- Deal with overlapping intervals
- Combine or find intersections/unions

**When to Use:**
- Problems involving time intervals
- Range merging
- Schedule conflicts

**Key Identifiers:**
- "Merge overlapping..."
- "Find conflicting..."
- Words like "intervals", "meetings", "schedule"
- Time range problems

**Example Problems:**
- Merge overlapping intervals
- Insert interval
- Meeting rooms required
- Employee free time

## 5. Binary Search
**Description:**
- Divide and conquer approach
- Reduces search space by half in each step
- Usually works on sorted arrays

**When to Use:**
- Sorted array searching
- Finding element position
- Finding minimum/maximum with specific conditions

**Key Identifiers:**
- "Find in sorted array..."
- "Minimum/Maximum value that satisfies..."
- Mentions of "sorted" or "ordered"
- "Efficient search"
- Log(n) time requirement mentioned

**Example Problems:**
- Search in rotated sorted array
- Find first/last position
- Search insert position
- Find minimum in rotated sorted array

## 6. DFS (Depth First Search)
**Description:**
- Explores as far as possible along each branch
- Uses stack (recursive or explicit)
- Good for tree/graph traversal

**When to Use:**
- Tree traversal problems
- Path finding
- Graph exploration
- Backtracking problems

**Key Identifiers:**
- "Find all paths..."
- "Explore all possibilities..."
- Tree/Graph traversal
- Words like "paths", "combinations"

**Example Problems:**
- Path sum in binary tree
- Number of islands
- Course schedule
- Word search

## 7. BFS (Breadth First Search)
**Description:**
- Explores all neighbors before moving to next level
- Uses queue
- Level by level traversal

**When to Use:**
- Shortest path problems
- Level order traversal
- Minimum steps problems

**Key Identifiers:**
- "Shortest path..."
- "Minimum steps to reach..."
- "Level order..."
- "Nearest/Closest..."

**Example Problems:**
- Level order traversal
- Word ladder
- Shortest path in binary matrix
- Rotting oranges

## 8. Dynamic Programming
**Description:**
- Breaks problem into smaller subproblems
- Stores results for reuse
- Optimizes recursive solutions

**When to Use:**
- Optimization problems
- Counting problems
- Problems with overlapping subproblems

**Key Identifiers:**
- "Maximum/Minimum ways..."
- "Count total number of ways..."
- "Can you reach..."
- Words like "optimal", "maximum profit"
- Fibonacci-like sequences

**Example Problems:**
- Climbing stairs
- Coin change
- Longest common subsequence
- House robber

## 9. Backtracking
**Description:**
- Build solutions incrementally
- Abandon solutions ("backtrack") when they cease to be valid
- Often uses recursion

**When to Use:**
- Permutation problems
- Combination problems
- Pattern matching
- Constraint satisfaction

**Key Identifiers:**
- "Find all possible..."
- "Generate all..."
- "List all combinations..."
- Words like "permutations", "combinations"

**Example Problems:**
- N-Queens
- Generate parentheses
- Palindrome partitioning
- Subsets/Combinations

## 10. Union Find (Disjoint Set)
**Description:**
- Tracks set of elements partitioned into disjoint sets
- Supports union and find operations
- Good for connectivity problems

**When to Use:**
- Graph connectivity problems
- Finding connected components
- Cycle detection in undirected graphs

**Key Identifiers:**
- "Connected components..."
- "Groups of connected..."
- Network connectivity
- "Find if connected..."

**Example Problems:**
- Number of connected components
- Redundant connection
- Friend circles
- Account merge


## 11. Monotonic Stack/Queue
**Description:**
- Stack/queue that maintains elements in increasing/decreasing order
- Elements violating monotonic property are removed

**When to Use:**
- Next greater/smaller element problems
- Temperature span problems
- Histogram problems

**Key Identifiers:**
- "Next greater element..."
- "Temperature span..."
- "Rectangle in histogram..."
- "View from side..."

**Example Problems:**
- Daily temperatures
- Next greater element
- Largest rectangle in histogram
- Remove K digits

## 12. Topological Sort
**Description:**
- Orders vertices in directed graph where for each edge (u,v), u comes before v
- Used for dependency scheduling

**When to Use:**
- Course scheduling problems
- Build system dependencies
- Task scheduling with prerequisites

**Key Identifiers:**
- "Prerequisites..."
- "Build order..."
- "Task dependencies..."
- "Course schedule..."

**Example Problems:**
- Course Schedule I & II
- Alien Dictionary
- Build System Dependencies
- Recipe Steps Ordering

## 13. Bit Manipulation
**Description:**
- Directly manipulate bits of numbers
- Uses bitwise operators (AND, OR, XOR, shift)

**When to Use:**
- Problems involving binary operations
- Space optimization
- Finding unique numbers

**Key Identifiers:**
- "Without using extra space..."
- "Find single number..."
- Binary operations mentioned
- Power of two/four checks

**Example Problems:**
- Single Number
- Power of Two
- Counting Bits
- Number of 1 Bits

## 14. Prefix Sum
**Description:**
- Precompute cumulative sums
- Answer range queries efficiently

**When to Use:**
- Range sum queries
- Continuous subarray sum problems
- Average in sliding window

**Key Identifiers:**
- "Sum of subarray..."
- "Range sum query..."
- "Continuous subarray sum..."
- "Average in window..."

**Example Problems:**
- Range Sum Query
- Continuous Subarray Sum
- Subarray Sum Equals K
- Number of Subarrays with Bounded Maximum

## 15. String Manipulation
**Description:**
- Pattern matching
- String transformations
- String comparisons

**When to Use:**
- Pattern matching problems
- String similarity problems
- String transformation problems

**Key Identifiers:**
- "String pattern..."
- "Word transformation..."
- "String matching..."
- "Edit distance..."

**Example Problems:**
- Edit Distance
- Regular Expression Matching
- String to Integer (atoi)
- Longest Common Prefix

## 16. Matrix Traversal
**Description:**
- Specific patterns for traversing 2D arrays
- Often involves spiral, diagonal, or boundary traversal

**When to Use:**
- Matrix rotation problems
- Spiral traversal
- Diagonal traversal
- Border processing

**Key Identifiers:**
- "Rotate matrix..."
- "Spiral order..."
- "Diagonal traverse..."
- "Border elements..."

**Example Problems:**
- Spiral Matrix
- Rotate Image
- Set Matrix Zeroes
- Word Search

## 17. Greedy Algorithms
**Description:**
- Makes locally optimal choice at each step
- Hopes to find global optimum

**When to Use:**
- Optimization problems
- Scheduling problems
- Resource allocation

**Key Identifiers:**
- "Maximum/Minimum possible..."
- "Optimal allocation..."
- "Scheduling tasks..."
- "Minimum number of..."

**Example Problems:**
- Jump Game
- Task Scheduler
- Gas Station
- Minimum Number of Arrows to Burst Balloons

## 18. Trie (Prefix Tree)
**Description:**
- Tree-like data structure for string operations
- Efficient for prefix-based operations

**When to Use:**
- Prefix matching problems
- Word dictionary problems
- Auto-complete features

**Key Identifiers:**
- "Word dictionary..."
- "Prefix matching..."
- "Auto-complete..."
- "Word search in grid..."

**Example Problems:**
- Implement Trie
- Word Search II
- Design Add and Search Words
- Replace Words

## 19. Rolling Hash
**Description:**
- Computing hash values for sliding window of text
- Useful for string pattern matching

**When to Use:**
- String matching problems
- Substring problems requiring quick comparison
- Pattern finding in strings

**Key Identifiers:**
- "Find all occurrences..."
- "Pattern matching in string..."
- "Repeated substring..."
- "String matching with wildcards..."

**Example Problems:**
- Repeated DNA Sequences
- Longest Duplicate Substring
- Implement strStr()
- Find All Anagrams in a String

## 20. Math and Geometry
**Description:**
- Mathematical properties and geometric concepts
- Often requires understanding of basic math principles

**When to Use:**
- Geometric problems
- Mathematical series problems
- Number theory problems

**Key Identifiers:**
- "Calculate area..."
- "Find pattern in series..."
- "Mathematical sequence..."
- "Geometric properties..."

**Example Problems:**
- Valid Square
- Perfect Squares
- Rectangle Overlap
- Max Points on a Line
