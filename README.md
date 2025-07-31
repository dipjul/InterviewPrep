# Ultimate ROI-Optimized Coding Interview Preparation Guide
*Data-Driven Approach for Maximum Interview Success*

## 📊 Overview

This guide organizes coding interview topics by **Return on Investment (ROI)** and **Learning Difficulty** based on comprehensive analysis of interview frequency and success rates. Study in the order presented for maximum efficiency.

---

## 📊 **ROI Methodology & Data Sources**

### **ROI Categories Explained:**

#### **High ROI Topics (Study First):**
- **Frequency:** 12-25% of interviews
- **Learning Time:** 5-15 hours to competency
- **Success Impact:** High - directly improves interview performance
- **Examples:** Arrays & Hashing, Two Pointers, BFS

#### **Medium ROI Topics (Study Second):**
- **Frequency:** 6-12% of interviews  
- **Learning Time:** 10-25 hours to competency
- **Success Impact:** Medium - important but more specialized
- **Examples:** Binary Search, Heap, Dynamic Programming

#### **Low ROI Topics (Study Last):**
- **Frequency:** 2-6% of interviews
- **Learning Time:** 15-40+ hours to competency
- **Success Impact:** Low - very specialized, high difficulty
- **Examples:** Trie, Union Find, Advanced Greedy

### **Limitations & Disclaimers:**
- **Data Recency:** Based on 2023-2024 interview patterns, may shift over time
- **Company Variation:** ROI may vary significantly by company size, type, and role level
- **Individual Differences:** Learning speeds and prior experience affect time investments
- **Sample Bias:** Data skewed toward tech companies and software engineering roles
- **Subjective Elements:** Success impact ratings based on community consensus

---

## 🎯 **HIGHEST ROI - Easy to Learn (Study These First!)**

### 1. Arrays & Hashing (Easy to Learn, High ROI)
**Why High ROI:** Fundamental building blocks, appears in 20-25% of interviews, essential for all other patterns.

#### Core Concept:
Master array manipulation and hash table operations - the foundation of most coding interview problems.

#### 🎯 Core Problems (Master These First):
1. **Contains Duplicate** (Easy) [LeetCode](https://leetcode.com/problems/contains-duplicate/) [NeetCode-150]
   - *Time: 10-15 min | Pattern: Hash set for duplicates*
2. **Valid Anagram** (Easy) [LeetCode](https://leetcode.com/problems/valid-anagram/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Character frequency counting*
3. **Two Sum** (Easy) [LeetCode](https://leetcode.com/problems/two-sum/) [Coding-Patterns, NeetCode-150]
   - *Time: 15-20 min | Pattern: Hash map lookup*
4. **Group Anagrams** (Medium) [LeetCode](https://leetcode.com/problems/group-anagrams/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Hash map with sorted keys*
5. **Top K Frequent Elements** (Medium) [LeetCode](https://leetcode.com/problems/top-k-frequent-elements/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Frequency counting + sorting*
6. **Product of Array Except Self** (Medium) [LeetCode](https://leetcode.com/problems/product-of-array-except-self/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Prefix/suffix arrays*
7. **Valid Sudoku** (Medium) [LeetCode](https://leetcode.com/problems/valid-sudoku/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Hash set validation*
8. **Longest Consecutive Sequence** (Medium) [LeetCode](https://leetcode.com/problems/longest-consecutive-sequence/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Hash set for O(n) sequence finding*

<details>
<summary>📚 <strong>Practice More Arrays & Hashing (6 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Encode And Decode Strings** (Medium) [LeetCode](https://leetcode.com/problems/encode-and-decode-strings/) [NeetCode-150]
- **First Non-repeating Character** (Easy) [LeetCode](https://leetcode.com/problems/first-unique-character-in-a-string/) [Coding-Patterns]
- **Largest Unique Number** (Easy) [LeetCode](https://leetcode.com/problems/largest-unique-number/) [Coding-Patterns]
- **Maximum Number of Balloons** (Easy) [LeetCode](https://leetcode.com/problems/maximum-number-of-balloons/) [Coding-Patterns]
- **Longest Palindrome** (Easy) [LeetCode](https://leetcode.com/problems/longest-palindrome/) [Coding-Patterns]
- **Ransom Note** (Easy) [LeetCode](https://leetcode.com/problems/ransom-note/) [Coding-Patterns]

</details>

#### Key Patterns:
- Hash map for O(1) lookups
- Frequency counting with hash maps
- Array prefix/suffix techniques
- Set operations for duplicates

---

### 2. Two Pointers (Easy to Learn, High ROI)
**Why High ROI:** Appears in 15-20% of interviews, quick to master, builds foundation for other techniques.

#### Core Concept:
Use two pointers moving towards each other or in the same direction to solve array/string problems efficiently.

#### 🎯 Core Problems (Master These First):
1. **Valid Palindrome** (Easy) [LeetCode](https://leetcode.com/problems/valid-palindrome/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Opposite direction pointers*
2. **Two Sum II - Input Array Is Sorted** (Easy) [LeetCode](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Opposite direction pointers*
3. **3Sum** (Medium) [LeetCode](https://leetcode.com/problems/3sum/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Fixed + moving pointers*
4. **Container With Most Water** (Medium) [LeetCode](https://leetcode.com/problems/container-with-most-water/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Greedy two pointers*
5. **Trapping Rain Water** (Hard) [LeetCode](https://leetcode.com/problems/trapping-rain-water/) [NeetCode-150]
   - *Time: 30-35 min | Pattern: Advanced two pointers*

<details>
<summary>📚 <strong>Practice More Two Pointers (8 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Remove Duplicates from Sorted Array** (Easy) [LeetCode](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) [Coding-Patterns]
- **Squares of a Sorted Array** (Easy) [LeetCode](https://leetcode.com/problems/squares-of-a-sorted-array/) [Coding-Patterns]
- **3Sum Closest** (Medium) [LeetCode](https://leetcode.com/problems/3sum-closest/) [Coding-Patterns]
- **4Sum** (Medium) [LeetCode](https://leetcode.com/problems/4sum/) [Coding-Patterns]
- **Subarray Product Less Than K** (Medium) [LeetCode](https://leetcode.com/problems/subarray-product-less-than-k/) [Coding-Patterns]

#### Fast & Slow Pointers (Cycle Detection):
- **Linked List Cycle** (Easy) [LeetCode](https://leetcode.com/problems/linked-list-cycle/) [Coding-Patterns, NeetCode-150]
- **Find the Duplicate Number** (Medium) [LeetCode](https://leetcode.com/problems/find-the-duplicate-number/) [NeetCode-150]
- **Happy Number** (Medium) [LeetCode](https://leetcode.com/problems/happy-number/) [Coding-Patterns]

</details>

#### Key Patterns:
- Opposite direction pointers (palindrome, two sum)
- Same direction pointers (remove duplicates)
- Fast & slow pointers (cycle detection)

---

### 3. Sliding Window (Easy to Learn, High ROI)
**Why High ROI:** 10-15% of interviews, excellent for string/array optimization problems.

#### Core Concept:
Maintain a window of elements and slide it to find optimal solutions without recalculating from scratch.

#### 🎯 Core Problems (Master These First):
1. **Best Time to Buy and Sell Stock** (Easy) [LeetCode](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Simple sliding window*
2. **Longest Substring Without Repeating Characters** (Medium) [LeetCode](https://leetcode.com/problems/longest-substring-without-repeating-characters/) [Coding-Patterns, NeetCode-150]
   - *Time: 20-25 min | Pattern: Variable window with hash set*
3. **Longest Repeating Character Replacement** (Medium) [LeetCode](https://leetcode.com/problems/longest-repeating-character-replacement/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Variable window with frequency count*
4. **Permutation in String** (Medium) [LeetCode](https://leetcode.com/problems/permutation-in-string/) [Coding-Patterns, NeetCode-150]
   - *Time: 20-25 min | Pattern: Fixed window with frequency matching*
5. **Minimum Window Substring** (Hard) [LeetCode](https://leetcode.com/problems/minimum-window-substring/) [Coding-Patterns, NeetCode-150]
   - *Time: 35-40 min | Pattern: Advanced variable window*

<details>
<summary>📚 <strong>Practice More Sliding Window (7 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Maximum Sum Subarray of Size K** (Easy) [Coding-Patterns]
- **Find All Anagrams in a String** (Medium) [LeetCode](https://leetcode.com/problems/find-all-anagrams-in-a-string/) [Coding-Patterns]
- **Fruit Into Baskets** (Medium) [LeetCode](https://leetcode.com/problems/fruit-into-baskets/) [Coding-Patterns]
- **Longest Substring with K Distinct Characters** (Medium) [Coding-Patterns]
- **Smallest Subarray with Given Sum** (Easy) [Coding-Patterns]
- **Sliding Window Maximum** (Hard) [LeetCode](https://leetcode.com/problems/sliding-window-maximum/) [NeetCode-150]
- **Longest Subarray with Ones after Replacement** (Hard) [LeetCode](https://leetcode.com/problems/max-consecutive-ones-iii/) [Coding-Patterns]

</details>

#### Key Patterns:
- Fixed-size window
- Variable-size window
- Window with character frequency tracking

---

### 4. Stack & Queue (Easy to Learn, High ROI)
**Why High ROI:** Appears in 12-15% of interviews, essential for parsing and monotonic problems.

#### Core Concept:
Use LIFO (stack) and FIFO (queue) data structures to solve parsing, matching, and ordering problems.

#### 🎯 Core Problems (Master These First):
1. **Valid Parentheses** (Easy) [LeetCode](https://leetcode.com/problems/valid-parentheses/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Stack for matching pairs*
2. **Min Stack** (Easy) [LeetCode](https://leetcode.com/problems/min-stack/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Auxiliary stack for min tracking*
3. **Evaluate Reverse Polish Notation** (Medium) [LeetCode](https://leetcode.com/problems/evaluate-reverse-polish-notation/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Stack for expression evaluation*
4. **Daily Temperatures** (Medium) [LeetCode](https://leetcode.com/problems/daily-temperatures/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Monotonic stack*
5. **Largest Rectangle in Histogram** (Hard) [LeetCode](https://leetcode.com/problems/largest-rectangle-in-histogram/) [NeetCode-150]
   - *Time: 35-40 min | Pattern: Advanced monotonic stack*

<details>
<summary>📚 <strong>Practice More Stack & Queue (2 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Generate Parentheses** (Medium) [LeetCode](https://leetcode.com/problems/generate-parentheses/) [NeetCode-150]
- **Car Fleet** (Medium) [LeetCode](https://leetcode.com/problems/car-fleet/) [NeetCode-150]

</details>

#### Key Patterns:
- Stack for matching and parsing
- Monotonic stack for next greater/smaller
- Queue for level-order processing
- Design problems with stacks

---

### 5. Breadth-First Search (Easy to Learn, High ROI)
**Why High ROI:** Fundamental for tree/graph problems, appears in 12-18% of interviews.

#### Core Concept:
Explore nodes level by level using a queue. Essential for shortest path and level-order problems.

#### 🎯 Core Problems (Master These First):
1. **Binary Tree Level Order Traversal** (Medium) [LeetCode](https://leetcode.com/problems/binary-tree-level-order-traversal/) [Coding-Patterns, NeetCode-150]
   - *Time: 20-25 min | Pattern: Basic level-order traversal*
2. **Maximum Depth of Binary Tree** (Easy) [LeetCode](https://leetcode.com/problems/maximum-depth-of-binary-tree/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: BFS depth counting*
3. **Number of Islands** (Medium) [LeetCode](https://leetcode.com/problems/number-of-islands/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Grid BFS*
4. **Rotting Oranges** (Medium) [LeetCode](https://leetcode.com/problems/rotting-oranges/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Multi-source BFS*
5. **Course Schedule** (Medium) [LeetCode](https://leetcode.com/problems/course-schedule/) [NeetCode-150]
   - *Time: 30-35 min | Pattern: Topological sort with BFS*

<details>
<summary>📚 <strong>Practice More BFS (10 Additional Problems)</strong></summary>

#### Tree BFS Problems:
- **Minimum Depth of Binary Tree** (Easy) [LeetCode](https://leetcode.com/problems/minimum-depth-of-binary-tree/) [Coding-Patterns]
- **Average of Levels in Binary Tree** (Easy) [LeetCode](https://leetcode.com/problems/average-of-levels-in-binary-tree/) [Coding-Patterns]
- **Binary Tree Level Order Traversal II** (Medium) [LeetCode](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/) [Coding-Patterns]
- **Binary Tree Zigzag Level Order Traversal** (Medium) [LeetCode](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) [Coding-Patterns]
- **Binary Tree Right Side View** (Medium) [LeetCode](https://leetcode.com/problems/binary-tree-right-side-view/) [Coding-Patterns, NeetCode-150]
- **Populating Next Right Pointers in Each Node** (Medium) [LeetCode](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/) [Coding-Patterns]

#### Graph BFS Problems:
- **Walls and Gates** (Medium) [LeetCode](https://leetcode.com/problems/walls-and-gates/) [NeetCode-150]
- **Clone Graph** (Medium) [LeetCode](https://leetcode.com/problems/clone-graph/) [NeetCode-150]
- **Word Ladder** (Hard) [LeetCode](https://leetcode.com/problems/word-ladder/) [NeetCode-150]
- **Alien Dictionary** (Hard) [LeetCode](https://leetcode.com/problems/alien-dictionary/) [NeetCode-150]

</details>

#### Key Patterns:
- Level-order traversal
- Shortest path in unweighted graphs
- Multi-source BFS

---

## 🔥 **HIGHEST ROI - Medium/High Difficulty (Study These Second)**

### 6. Depth-First Search (Medium to Learn, High ROI)
**Why High ROI:** Core technique for trees/graphs, backtracking foundation. 15-25% of interviews.

#### Core Concept:
Explore as far as possible along each branch before backtracking. Essential for tree traversals and path problems.

#### 🎯 Core Problems (Master These First):
1. **Invert Binary Tree** (Easy) [LeetCode](https://leetcode.com/problems/invert-binary-tree/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Tree transformation*
2. **Validate Binary Search Tree** (Medium) [LeetCode](https://leetcode.com/problems/validate-binary-search-tree/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Tree validation with bounds*
3. **Diameter of Binary Tree** (Medium) [LeetCode](https://leetcode.com/problems/diameter-of-binary-tree/) [Coding-Patterns, NeetCode-150]
   - *Time: 20-25 min | Pattern: Tree metrics calculation*
4. **Course Schedule** (Medium) [LeetCode](https://leetcode.com/problems/course-schedule/) [NeetCode-150]
   - *Time: 30-35 min | Pattern: Cycle detection in directed graph*
5. **Binary Tree Maximum Path Sum** (Hard) [LeetCode](https://leetcode.com/problems/binary-tree-maximum-path-sum/) [Coding-Patterns, NeetCode-150]
   - *Time: 35-40 min | Pattern: Advanced tree path problems*

<details>
<summary>📚 <strong>Practice More DFS (15 Additional Problems)</strong></summary>

#### Tree DFS Problems:
- **Same Tree** (Easy) [LeetCode](https://leetcode.com/problems/same-tree/) [NeetCode-150]
- **Path Sum** (Easy) [LeetCode](https://leetcode.com/problems/path-sum/) [Coding-Patterns]
- **Subtree of Another Tree** (Easy) [LeetCode](https://leetcode.com/problems/subtree-of-another-tree/) [NeetCode-150]
- **Balanced Binary Tree** (Easy) [LeetCode](https://leetcode.com/problems/balanced-binary-tree/) [NeetCode-150]
- **Kth Smallest Element in a BST** (Medium) [LeetCode](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) [NeetCode-150]
- **Construct Binary Tree from Preorder and Inorder Traversal** (Medium) [LeetCode](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) [NeetCode-150]
- **Path Sum II** (Medium) [LeetCode](https://leetcode.com/problems/path-sum-ii/) [Coding-Patterns]
- **Path Sum III** (Medium) [LeetCode](https://leetcode.com/problems/path-sum-iii/)
- **Sum Root to Leaf Numbers** (Medium) [LeetCode](https://leetcode.com/problems/sum-root-to-leaf-numbers/) [Coding-Patterns]
- **Lowest Common Ancestor of a Binary Tree** (Medium) [LeetCode](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) [NeetCode-150]
- **House Robber III** (Medium) [LeetCode](https://leetcode.com/problems/house-robber-iii/) [NeetCode-150]
- **Serialize and Deserialize Binary Tree** (Hard) [LeetCode](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) [NeetCode-150]

#### Graph DFS Problems:
- **Clone Graph** (Medium) [LeetCode](https://leetcode.com/problems/clone-graph/) [NeetCode-150]
- **Course Schedule II** (Medium) [LeetCode](https://leetcode.com/problems/course-schedule-ii/) [NeetCode-150]
- **Pacific Atlantic Water Flow** (Medium) [LeetCode](https://leetcode.com/problems/pacific-atlantic-water-flow/) [NeetCode-150]

</details>

#### Key Patterns:
- Tree traversals (preorder, inorder, postorder)
- Path sum problems
- Graph cycle detection
- Topological sorting

---

### 7. Backtracking (High Difficulty to Learn, High ROI)
**Why High ROI:** Appears in 8-12% of interviews, but critical for senior roles and complex problem-solving.

#### Core Concept:
Systematically explore all possible solutions by building candidates incrementally and abandoning those that cannot lead to a valid solution.

#### 🎯 Core Problems (Master These First):
1. **Subsets** (Medium) [LeetCode](https://leetcode.com/problems/subsets/) [Coding-Patterns, NeetCode-150]
   - *Time: 20-25 min | Pattern: Generate all combinations*
2. **Permutations** (Medium) [LeetCode](https://leetcode.com/problems/permutations/) [Coding-Patterns, NeetCode-150]
   - *Time: 20-25 min | Pattern: Generate all arrangements*
3. **Combination Sum** (Medium) [LeetCode](https://leetcode.com/problems/combination-sum/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Target sum with reuse*
4. **Word Search** (Medium) [LeetCode](https://leetcode.com/problems/word-search/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Grid backtracking*
5. **Generate Parentheses** (Medium) [LeetCode](https://leetcode.com/problems/generate-parentheses/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Constraint-based generation*
6. **N-Queens** (Hard) [LeetCode](https://leetcode.com/problems/n-queens/) [Coding-Patterns, NeetCode-150]
   - *Time: 35-40 min | Pattern: Constraint satisfaction*

<details>
<summary>📚 <strong>Practice More Backtracking (6 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Subsets II** (Medium) [LeetCode](https://leetcode.com/problems/subsets-ii/) [NeetCode-150]
- **Combination Sum II** (Medium) [LeetCode](https://leetcode.com/problems/combination-sum-ii/) [NeetCode-150]
- **Palindrome Partitioning** (Medium) [LeetCode](https://leetcode.com/problems/palindrome-partitioning/) [NeetCode-150]
- **Letter Combinations of a Phone Number** (Medium) [LeetCode](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) [NeetCode-150]
- **Sudoku Solver** (Hard) [LeetCode](https://leetcode.com/problems/sudoku-solver/) [Coding-Patterns]
- **Word Search II** (Hard) [LeetCode](https://leetcode.com/problems/word-search-ii/) [NeetCode-150]

</details>

#### Key Patterns:
- Generate all combinations/permutations
- Constraint satisfaction problems
- Path finding with constraints
- Decision tree exploration

---

## 📊 **Progress Tracking - High ROI Topics**

- [ ] **Arrays & Hashing** - Easy to Learn ✅ Foundation
  - [ ] Master hash map operations
  - [ ] Solve 6+ essential problems
  - [ ] Understand frequency counting patterns

- [ ] **Two Pointers** - Easy to Learn ✅ Foundation
  - [ ] Master basic two-pointer technique
  - [ ] Solve 5+ essential problems
  - [ ] Understand fast/slow pointer variation

- [ ] **Sliding Window** - Easy to Learn ✅ Foundation  
  - [ ] Master fixed and variable window techniques
  - [ ] Solve 5+ essential problems
  - [ ] Handle character frequency tracking

- [ ] **Stack & Queue** - Easy to Learn ✅ Foundation
  - [ ] Master stack operations and parsing
  - [ ] Solve 5+ essential problems
  - [ ] Understand monotonic stack patterns

- [ ] **Breadth-First Search** - Easy to Learn ✅ Foundation
  - [ ] Master level-order traversal
  - [ ] Solve tree and graph BFS problems
  - [ ] Understand multi-source BFS

- [ ] **Depth-First Search** - Medium Difficulty 🔥 Advanced
  - [ ] Master tree DFS patterns
  - [ ] Solve graph DFS problems
  - [ ] Understand topological sorting

- [ ] **Backtracking** - High Difficulty 🔥 Advanced
  - [ ] Master decision tree exploration
  - [ ] Solve constraint satisfaction problems
  - [ ] Handle complex state management

---

## 🎯 **Study Plan Recommendations**

### 1-2 Weeks (Crash Course)
Focus **ONLY** on Easy + High ROI topics:
1. Arrays & Hashing (2-3 days) - 8 core problems
2. Two Pointers (2-3 days) - 5 core problems
3. Sliding Window (2-3 days) - 5 core problems
4. Stack & Queue (1-2 days) - 5 core problems
5. Breadth-First Search (2-3 days) - 5 core problems

**Expected Outcome:** Cover 45-60% of common interview patterns

### 1 Month (Balanced Approach)
Complete all High ROI topics:
1. Week 1: Arrays & Hashing + Two Pointers
2. Week 2: Sliding Window + Stack & Queue
3. Week 3: Breadth-First Search + Basic DFS
4. Week 4: Advanced DFS + Backtracking fundamentals

**Expected Outcome:** Cover 70-85% of interview patterns

### 2+ Months (Comprehensive)
Add Medium ROI topics after mastering High ROI:
- Month 1: All High ROI topics (complete mastery)
- Month 2: Binary Search + Heap + Intervals
- Month 3+: Dynamic Programming + Linked Lists + Low ROI topics
- Focus on depth over breadth
- Practice system design integration

---

*Continue to Medium ROI section after mastering these High ROI topics...*
## 
💪 **MEDIUM ROI - Study These Third**

### 8. Binary Search (Easy to Learn, Medium ROI)
**Why Medium ROI:** Appears in 8-12% of interviews, but essential for optimization problems.

#### Core Concept:
Efficiently search sorted arrays or search spaces by repeatedly dividing the problem in half.

#### 🎯 Core Problems (Master These First):
1. **Binary Search** (Easy) [LeetCode](https://leetcode.com/problems/binary-search/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Classic binary search*
2. **Search in Rotated Sorted Array** (Medium) [LeetCode](https://leetcode.com/problems/search-in-rotated-sorted-array/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Modified binary search*
3. **Find Minimum in Rotated Sorted Array** (Medium) [LeetCode](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Find pivot in rotated array*
4. **Koko Eating Bananas** (Medium) [LeetCode](https://leetcode.com/problems/koko-eating-bananas/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Binary search on answer*
5. **Median of Two Sorted Arrays** (Hard) [LeetCode](https://leetcode.com/problems/median-of-two-sorted-arrays/) [Coding-Patterns, NeetCode-150]
   - *Time: 35-40 min | Pattern: Advanced binary search*

<details>
<summary>📚 <strong>Practice More Binary Search (10 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Search a 2D Matrix** (Medium) [LeetCode](https://leetcode.com/problems/search-a-2d-matrix/) [Coding-Patterns, NeetCode-150]
- **Time Based Key-Value Store** (Medium) [LeetCode](https://leetcode.com/problems/time-based-key-value-store/) [NeetCode-150]
- **Find First and Last Position of Element in Sorted Array** (Medium) [LeetCode](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) [Coding-Patterns]
- **Search in Rotated Sorted Array II** (Medium) [LeetCode](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/) [Coding-Patterns]
- **Find Peak Element** (Medium) [LeetCode](https://leetcode.com/problems/find-peak-element/) [Coding-Patterns]
- **Capacity To Ship Packages Within D Days** (Medium) [LeetCode](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/) [Coding-Patterns]
- **Minimum Number of Days to Make m Bouquets** (Medium) [LeetCode](https://leetcode.com/problems/minimum-number-of-days-to-make-m-bouquets/) [Coding-Patterns]
- **Sqrt(x)** (Easy) [LeetCode](https://leetcode.com/problems/sqrtx/) [NeetCode-150]
- **Pow(x, n)** (Medium) [LeetCode](https://leetcode.com/problems/powx-n/) [NeetCode-150]
- **Search Bitonic Array** (Medium) [LeetCode](https://leetcode.com/problems/find-in-mountain-array/) [Coding-Patterns]

</details>

#### Key Patterns:
- Classic binary search on sorted arrays
- Binary search on rotated arrays
- Binary search on answer (optimization problems)
- 2D matrix search

---

### 9. Heap (Medium to Learn, Medium ROI)
**Why Medium ROI:** 6-10% of interviews, crucial for priority-based problems and top-K scenarios.

#### Core Concept:
Use heap data structure to efficiently maintain ordered elements and solve priority-based problems.

#### 🎯 Core Problems (Master These First):
1. **Kth Largest Element in a Stream** (Easy) [LeetCode](https://leetcode.com/problems/kth-largest-element-in-a-stream/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Min heap for top K*
2. **Last Stone Weight** (Easy) [LeetCode](https://leetcode.com/problems/last-stone-weight/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Max heap simulation*
3. **K Closest Points to Origin** (Medium) [LeetCode](https://leetcode.com/problems/k-closest-points-to-origin/) [Coding-Patterns, NeetCode-150]
   - *Time: 20-25 min | Pattern: Min heap with custom comparator*
4. **Top K Frequent Elements** (Medium) [LeetCode](https://leetcode.com/problems/top-k-frequent-elements/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Frequency counting + heap*
5. **Find Median from Data Stream** (Hard) [LeetCode](https://leetcode.com/problems/find-median-from-data-stream/) [Coding-Patterns, NeetCode-150]
   - *Time: 35-40 min | Pattern: Two heaps (max + min)*

<details>
<summary>📚 <strong>Practice More Heap (2 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Merge k Sorted Lists** (Hard) [LeetCode](https://leetcode.com/problems/merge-k-sorted-lists/) [Coding-Patterns, NeetCode-150]
- **Task Scheduler** (Medium) [LeetCode](https://leetcode.com/problems/task-scheduler/) [NeetCode-150]

</details>

#### Key Patterns:
- Top K elements
- Two heaps (median finding)
- K-way merge
- Priority scheduling

---

### 10. Intervals (Medium to Learn, Medium ROI)
**Why Medium ROI:** Appears in 8-12% of interviews, essential for scheduling and time-based problems.

#### Core Concept:
Work with time intervals, ranges, and overlapping periods to solve scheduling, merging, and optimization problems.

#### 🎯 Core Problems (Master These First):
1. **Merge Intervals** (Medium) [LeetCode](https://leetcode.com/problems/merge-intervals/) [Coding-Patterns, NeetCode-150]
   - *Time: 20-25 min | Pattern: Sort and merge overlapping intervals*
2. **Insert Interval** (Medium) [LeetCode](https://leetcode.com/problems/insert-interval/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Insert and merge in sorted intervals*
3. **Non Overlapping Intervals** (Medium) [LeetCode](https://leetcode.com/problems/non-overlapping-intervals/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Greedy interval scheduling*
4. **Meeting Rooms** (Easy) [LeetCode](https://leetcode.com/problems/meeting-rooms/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Check for overlapping intervals*
5. **Meeting Rooms II** (Medium) [LeetCode](https://leetcode.com/problems/meeting-rooms-ii/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Minimum rooms needed*

<details>
<summary>📚 <strong>Practice More Intervals (3 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Intervals Intersection** (Medium) [LeetCode](https://leetcode.com/problems/interval-list-intersections/) [Coding-Patterns]
- **Maximum CPU Load** (Hard) [GeeksforGeeks](https://www.geeksforgeeks.org/maximum-cpu-load-from-the-given-list-of-jobs/) [Coding-Patterns]
- **Employee Free Time** (Hard) [LeetCode](https://leetcode.com/problems/employee-free-time/) [Coding-Patterns]

</details>

#### Key Patterns:
- Sort intervals by start time
- Merge overlapping intervals
- Greedy scheduling algorithms
- Priority queue for interval management

---

### 11. Cyclic Sort (Easy to Learn, Medium ROI)
**Why Medium ROI:** Appears in 6-10% of interviews, specialized but efficient pattern for array problems.

#### Core Concept:
Sort arrays containing numbers in a given range by placing each number at its correct index position.

#### 🎯 Core Problems (Master These First):
1. **Missing Number** (Easy) [LeetCode](https://leetcode.com/problems/missing-number/) [Coding-Patterns, NeetCode-150]
   - *Time: 15-20 min | Pattern: Cyclic sort to find missing*
2. **Find the Duplicate Number** (Medium) [LeetCode](https://leetcode.com/problems/find-the-duplicate-number/) [Coding-Patterns, NeetCode-150]
   - *Time: 20-25 min | Pattern: Cyclic sort or Floyd's algorithm*
3. **Find All Numbers Disappeared in an Array** (Easy) [LeetCode](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/) [Coding-Patterns]
   - *Time: 20-25 min | Pattern: Mark visited indices*
4. **Find All Duplicates in an Array** (Medium) [LeetCode](https://leetcode.com/problems/find-all-duplicates-in-an-array/) [Coding-Patterns]
   - *Time: 20-25 min | Pattern: Mark visited with negation*
5. **First Missing Positive** (Hard) [LeetCode](https://leetcode.com/problems/first-missing-positive/) [Coding-Patterns]
   - *Time: 30-35 min | Pattern: Cyclic sort with constraints*

<details>
<summary>📚 <strong>Practice More Cyclic Sort (4 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Cyclic Sort** (Easy) [GeeksforGeeks](https://www.geeksforgeeks.org/sort-an-array-which-contain-1-to-n-values-in-on-using-cycle-sort/) [Coding-Patterns]
- **Find the Corrupt Pair** (Easy) [TheCodingSimplified](https://thecodingsimplified.com/find-currupt-pair/) [Coding-Patterns]
- **Find the First K Missing Positive Numbers** (Hard) [TheCodingSimplified](https://thecodingsimplified.com/find-the-first-k-missing-positive-number/) [Coding-Patterns]
- **Smallest Missing Positive Number** (Medium) [LeetCode](https://leetcode.com/problems/first-missing-positive/) [Coding-Patterns]

</details>

#### Key Patterns:
- Place elements at correct indices
- Use array indices as hash map
- Mark visited elements
- Handle duplicates and missing numbers

---

### 12. K-way Merge (Medium to Learn, Medium ROI)
**Why Medium ROI:** Appears in 5-8% of interviews, important for merge operations and priority queues.

#### Core Concept:
Merge multiple sorted arrays or lists using heap/priority queue for efficient sorting.

#### 🎯 Core Problems (Master These First):
1. **Merge k Sorted Lists** (Hard) [LeetCode](https://leetcode.com/problems/merge-k-sorted-lists/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Min heap for k-way merge*
2. **Kth Smallest Element in a Sorted Matrix** (Medium) [LeetCode](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/) [Coding-Patterns]
   - *Time: 25-30 min | Pattern: Min heap with matrix traversal*
3. **Smallest Range Covering Elements from K Lists** (Hard) [LeetCode](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) [Coding-Patterns]
   - *Time: 35-40 min | Pattern: Min heap with range tracking*

<details>
<summary>📚 <strong>Practice More K-way Merge (3 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Kth Smallest Number in M Sorted Lists** (Medium) [GeeksforGeeks](https://www.geeksforgeeks.org/find-m-th-smallest-value-in-k-sorted-arrays/) [Coding-Patterns]
- **K Pairs with Largest Sums** (Medium) [LeetCode](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/) [Coding-Patterns]
- **Merge Sorted Array** (Easy) [LeetCode](https://leetcode.com/problems/merge-sorted-array/) [NeetCode-150]

</details>

#### Key Patterns:
- Min heap for k-way merge
- Priority queue with custom comparators
- Merge multiple sorted sequences
- Kth element in merged result

---

### 13. Dynamic Programming (High Difficulty to Learn, Medium ROI)
**Why Medium ROI:** 10-15% of interviews, but high difficulty makes it lower ROI for time-constrained prep.

#### Core Concept:
Break down complex problems into simpler subproblems and store results to avoid redundant calculations.

#### 🎯 Core Problems (Master These First):
1. **Climbing Stairs** (Easy) [LeetCode](https://leetcode.com/problems/climbing-stairs/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Basic 1-D DP*
2. **House Robber** (Medium) [LeetCode](https://leetcode.com/problems/house-robber/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Decision-based DP*
3. **Coin Change** (Medium) [LeetCode](https://leetcode.com/problems/coin-change/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Unbounded knapsack*
4. **Unique Paths** (Medium) [LeetCode](https://leetcode.com/problems/unique-paths/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: 2-D grid DP*
5. **Longest Common Subsequence** (Medium) [LeetCode](https://leetcode.com/problems/longest-common-subsequence/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: 2-D string DP*

<details>
<summary>📚 <strong>Practice More Dynamic Programming (8 Additional Problems)</strong></summary>

#### 1-D DP Problems:
- **House Robber II** (Medium) [LeetCode](https://leetcode.com/problems/house-robber-ii/) [NeetCode-150]
- **Longest Increasing Subsequence** (Medium) [LeetCode](https://leetcode.com/problems/longest-increasing-subsequence/) [NeetCode-150]
- **Word Break** (Medium) [LeetCode](https://leetcode.com/problems/word-break/) [NeetCode-150]
- **Decode Ways** (Medium) [LeetCode](https://leetcode.com/problems/decode-ways/) [NeetCode-150]

#### 2-D DP Problems:
- **Edit Distance** (Hard) [LeetCode](https://leetcode.com/problems/edit-distance/) [NeetCode-150]
- **Partition Equal Subset Sum** (Medium) [LeetCode](https://leetcode.com/problems/partition-equal-subset-sum/) [Coding-Patterns, NeetCode-150]
- **0/1 Knapsack** (Medium) [GeeksforGeeks](https://www.geeksforgeeks.org/0-1-knapsack-problem-dp-10/) [Coding-Patterns]
- **Target Sum** (Medium) [LeetCode](https://leetcode.com/problems/target-sum/) [NeetCode-150]

</details>

#### Key Patterns:
- 1-D DP (linear problems)
- 2-D DP (grid/string problems)
- Knapsack variations
- State machine DP

---

## 📚 **LOW ROI - Study These Last (Time Permitting)**

### 11. Linked Lists (Easy to Learn, Medium ROI)
**Why Medium ROI:** 6-10% of interviews, fundamental data structure with many variations.

#### Core Concept:
Master linked list manipulation, pointer techniques, and common operations for dynamic data structures.

#### 🎯 Core Problems (Master These First):
1. **Reverse Linked List** (Easy) [LeetCode](https://leetcode.com/problems/reverse-linked-list/) [Coding-Patterns, NeetCode-150]
   - *Time: 15-20 min | Pattern: Iterative pointer reversal*
2. **Merge Two Sorted Lists** (Easy) [LeetCode](https://leetcode.com/problems/merge-two-sorted-lists/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Two-pointer merging*
3. **Linked List Cycle** (Easy) [LeetCode](https://leetcode.com/problems/linked-list-cycle/) [Coding-Patterns, NeetCode-150]
   - *Time: 15-20 min | Pattern: Fast & slow pointers*
4. **Remove Nth Node From End of List** (Medium) [LeetCode](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Two-pointer with gap*
5. **Reorder List** (Medium) [LeetCode](https://leetcode.com/problems/reorder-list/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Find middle + reverse + merge*
6. **Add Two Numbers** (Medium) [LeetCode](https://leetcode.com/problems/add-two-numbers/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Digit-by-digit addition with carry*
7. **Copy List With Random Pointer** (Medium) [LeetCode](https://leetcode.com/problems/copy-list-with-random-pointer/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Hash map for node mapping*

<details>
<summary>📚 <strong>Practice More Linked Lists (8 Additional Problems)</strong></summary>

#### Advanced Linked List Problems:
- **Reverse Linked List II** (Medium) [LeetCode](https://leetcode.com/problems/reverse-linked-list-ii/) [Coding-Patterns]
- **Reverse Nodes in k-Group** (Hard) [LeetCode](https://leetcode.com/problems/reverse-nodes-in-k-group/) [Coding-Patterns, NeetCode-150]
- **Rotate List** (Medium) [LeetCode](https://leetcode.com/problems/rotate-list/) [Coding-Patterns]
- **Palindrome Linked List** (Easy) [LeetCode](https://leetcode.com/problems/palindrome-linked-list/) [Coding-Patterns]
- **Merge k Sorted Lists** (Hard) [LeetCode](https://leetcode.com/problems/merge-k-sorted-lists/) [NeetCode-150]
- **LRU Cache** (Medium) [LeetCode](https://leetcode.com/problems/lru-cache/) [NeetCode-150]
- **Linked List Cycle II** (Medium) [LeetCode](https://leetcode.com/problems/linked-list-cycle-ii/) [Coding-Patterns]
- **Middle of the Linked List** (Easy) [LeetCode](https://leetcode.com/problems/middle-of-the-linked-list/) [Coding-Patterns]

</details>

#### Key Patterns:
- Pointer manipulation and reversal
- Two-pointer techniques (fast/slow, gap)
- Dummy node usage for edge cases
- Hash map for complex node relationships

---

### 12. Bit Manipulation (Easy to Learn, Low ROI)
**Why Low ROI:** 3-5% of interviews, quick to master but rarely appears.

#### Essential Problems:
- **Single Number** (Easy) [LeetCode](https://leetcode.com/problems/single-number/) [NeetCode-150]
- **Number of 1 Bits** (Easy) [LeetCode](https://leetcode.com/problems/number-of-1-bits/) [NeetCode-150]
- **Counting Bits** (Easy) [LeetCode](https://leetcode.com/problems/counting-bits/) [NeetCode-150]
- **Missing Number** (Easy) [LeetCode](https://leetcode.com/problems/missing-number/) [NeetCode-150]
- **Reverse Bits** (Easy) [LeetCode](https://leetcode.com/problems/reverse-bits/) [NeetCode-150]

#### Key Patterns:
- XOR for finding unique elements
- Bit masking and manipulation
- Power of 2 operations

---

### 13. Trie (Medium to Learn, Low ROI)
**Why Low ROI:** 2-4% of interviews, specialized use cases.

#### Essential Problems:
- **Implement Trie (Prefix Tree)** (Medium) [LeetCode](https://leetcode.com/problems/implement-trie-prefix-tree/) [Coding-Patterns, NeetCode-150]
- **Design Add and Search Words Data Structure** (Medium) [LeetCode](https://leetcode.com/problems/design-add-and-search-words-data-structure/) [NeetCode-150]
- **Word Search II** (Hard) [LeetCode](https://leetcode.com/problems/word-search-ii/) [NeetCode-150]

#### Key Patterns:
- Prefix matching
- Auto-complete systems
- Word games and puzzles

---

### 14. Union Find (Medium to Learn, Low ROI)
**Why Low ROI:** 2-3% of interviews, very specialized.

#### Essential Problems:
- **Number of Connected Components in an Undirected Graph** (Medium) [LeetCode](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/) [NeetCode-150]
- **Redundant Connection** (Medium) [LeetCode](https://leetcode.com/problems/redundant-connection/) [Coding-Patterns, NeetCode-150]

#### Key Patterns:
- Connected components
- Cycle detection in undirected graphs
- Dynamic connectivity

---

### 15. Math & Geometry (Medium to Learn, Low ROI)
**Why Low ROI:** 3-5% of interviews, specialized mathematical problems.

#### Core Concept:
Solve problems involving mathematical calculations, geometric operations, and matrix manipulations.

#### 🎯 Core Problems (Master These First):
1. **Rotate Image** (Medium) [LeetCode](https://leetcode.com/problems/rotate-image/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Matrix rotation in-place*
2. **Spiral Matrix** (Medium) [LeetCode](https://leetcode.com/problems/spiral-matrix/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Matrix traversal with boundaries*
3. **Set Matrix Zeroes** (Medium) [LeetCode](https://leetcode.com/problems/set-matrix-zeroes/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Matrix modification with space optimization*
4. **Plus One** (Easy) [LeetCode](https://leetcode.com/problems/plus-one/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Array arithmetic with carry*
5. **Multiply Strings** (Medium) [LeetCode](https://leetcode.com/problems/multiply-strings/) [NeetCode-150]
   - *Time: 30-35 min | Pattern: String arithmetic simulation*

<details>
<summary>📚 <strong>Practice More Math & Geometry (3 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Happy Number** (Easy) [LeetCode](https://leetcode.com/problems/happy-number/) [NeetCode-150]
- **Pow(x, n)** (Medium) [LeetCode](https://leetcode.com/problems/powx-n/) [NeetCode-150]
- **Detect Squares** (Medium) [LeetCode](https://leetcode.com/problems/detect-squares/) [NeetCode-150]

</details>

#### Key Patterns:
- Matrix manipulation and traversal
- Mathematical simulation
- Geometric calculations
- Number theory problems

---

### 16. Advanced Graphs (High to Learn, Low ROI)
**Why Low ROI:** 2-4% of interviews, very specialized graph algorithms.

#### Core Concept:
Advanced graph algorithms including shortest paths, minimum spanning trees, and complex graph traversals.

#### 🎯 Core Problems (Master These First):
1. **Network Delay Time** (Medium) [LeetCode](https://leetcode.com/problems/network-delay-time/) [NeetCode-150]
   - *Time: 30-35 min | Pattern: Dijkstra's shortest path*
2. **Min Cost to Connect All Points** (Medium) [LeetCode](https://leetcode.com/problems/min-cost-to-connect-all-points/) [NeetCode-150]
   - *Time: 30-35 min | Pattern: Minimum spanning tree (Prim's)*
3. **Cheapest Flights Within K Stops** (Medium) [LeetCode](https://leetcode.com/problems/cheapest-flights-within-k-stops/) [NeetCode-150]
   - *Time: 35-40 min | Pattern: Modified Dijkstra with constraints*

<details>
<summary>📚 <strong>Practice More Advanced Graphs (3 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Reconstruct Itinerary** (Hard) [LeetCode](https://leetcode.com/problems/reconstruct-itinerary/) [NeetCode-150]
- **Swim In Rising Water** (Hard) [LeetCode](https://leetcode.com/problems/swim-in-rising-water/) [NeetCode-150]
- **Alien Dictionary** (Hard) [LeetCode](https://leetcode.com/problems/alien-dictionary/) [NeetCode-150]

</details>

#### Key Patterns:
- Dijkstra's algorithm
- Minimum spanning tree (Prim's/Kruskal's)
- Bellman-Ford algorithm
- Advanced graph traversal

---

### 17. Topological Sort (Medium to Learn, Low ROI)
**Why Low ROI:** 2-3% of interviews, specialized for dependency problems.

#### Core Concept:
Order vertices in a directed acyclic graph such that for every directed edge, the source comes before the destination.

#### 🎯 Core Problems (Master These First):
1. **Course Schedule** (Medium) [LeetCode](https://leetcode.com/problems/course-schedule/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Cycle detection with topological sort*
2. **Course Schedule II** (Medium) [LeetCode](https://leetcode.com/problems/course-schedule-ii/) [Coding-Patterns, NeetCode-150]
   - *Time: 25-30 min | Pattern: Topological ordering*
3. **Alien Dictionary** (Hard) [LeetCode](https://leetcode.com/problems/alien-dictionary/) [Coding-Patterns, NeetCode-150]
   - *Time: 35-40 min | Pattern: Build graph from constraints*

<details>
<summary>📚 <strong>Practice More Topological Sort (5 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Minimum Height Trees** (Medium) [LeetCode](https://leetcode.com/problems/minimum-height-trees/) [Coding-Patterns]
- **Sequence Reconstruction** (Medium) [LeetCode](https://leetcode.com/problems/sequence-reconstruction/) [Coding-Patterns]
- **All Ancestors of a Node in a Directed Acyclic Graph** (Medium) [LeetCode](https://leetcode.com/problems/all-ancestors-of-a-node-in-a-directed-acyclic-graph/)
- **Find All Possible Recipes from Given Supplies** (Medium) [LeetCode](https://leetcode.com/problems/find-all-possible-recipes-from-given-supplies/)
- **Parallel Courses** (Medium) [LeetCode](https://leetcode.com/problems/parallel-courses/)

</details>

#### Key Patterns:
- Kahn's algorithm (BFS-based)
- DFS-based topological sort
- Cycle detection in directed graphs
- Dependency resolution

---

### 18. String Manipulation (Easy to Learn, Low ROI)
**Why Low ROI:** 4-6% of interviews, often covered in other topics.

#### Core Concept:
Advanced string processing, pattern matching, and text manipulation algorithms.

#### 🎯 Core Problems (Master These First):
1. **Longest Palindromic Substring** (Medium) [LeetCode](https://leetcode.com/problems/longest-palindromic-substring/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Expand around centers*
2. **Palindromic Substrings** (Medium) [LeetCode](https://leetcode.com/problems/palindromic-substrings/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Count palindromes*
3. **Valid Palindrome II** (Easy) [LeetCode](https://leetcode.com/problems/valid-palindrome-ii/) [Coding-Patterns]
   - *Time: 20-25 min | Pattern: Palindrome with one deletion*
4. **Implement strStr()** (Easy) [LeetCode](https://leetcode.com/problems/implement-strstr/) [Coding-Patterns]
   - *Time: 20-25 min | Pattern: String matching (KMP)*

<details>
<summary>📚 <strong>Practice More String Manipulation (4 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **String to Integer (atoi)** (Medium) [LeetCode](https://leetcode.com/problems/string-to-integer-atoi/)
- **Reverse Words in a String** (Medium) [LeetCode](https://leetcode.com/problems/reverse-words-in-a-string/)
- **Longest Common Prefix** (Easy) [LeetCode](https://leetcode.com/problems/longest-common-prefix/)
- **Valid Number** (Hard) [LeetCode](https://leetcode.com/problems/valid-number/)

</details>

#### Key Patterns:
- Palindrome detection and expansion
- String parsing and validation
- Pattern matching algorithms
- Text processing and manipulation

---

### 19. Greedy (High Difficulty to Learn, Low ROI)
**Why Low ROI:** 4-6% of interviews, but high difficulty and problem-specific nature makes it low ROI.

#### Core Concept:
Make locally optimal choices at each step to find a global optimum.

#### 🎯 Core Problems (Master These First):
1. **Maximum Subarray** (Easy) [LeetCode](https://leetcode.com/problems/maximum-subarray/) [NeetCode-150]
   - *Time: 15-20 min | Pattern: Kadane's algorithm*
2. **Jump Game** (Medium) [LeetCode](https://leetcode.com/problems/jump-game/) [NeetCode-150]
   - *Time: 20-25 min | Pattern: Greedy reachability*
3. **Jump Game II** (Medium) [LeetCode](https://leetcode.com/problems/jump-game-ii/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Greedy minimum jumps*
4. **Gas Station** (Medium) [LeetCode](https://leetcode.com/problems/gas-station/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Greedy circular array*
5. **Hand of Straights** (Medium) [LeetCode](https://leetcode.com/problems/hand-of-straights/) [NeetCode-150]
   - *Time: 25-30 min | Pattern: Greedy grouping*

<details>
<summary>📚 <strong>Practice More Greedy (8 Additional Problems)</strong></summary>

#### Additional Essential Problems:
- **Valid Parenthesis String** (Medium) [LeetCode](https://leetcode.com/problems/valid-parenthesis-string/) [NeetCode-150]
- **Partition Labels** (Medium) [LeetCode](https://leetcode.com/problems/partition-labels/) [NeetCode-150]
- **Merge Triplets to Form Target Triplet** (Medium) [LeetCode](https://leetcode.com/problems/merge-triplets-to-form-target-triplet/) [NeetCode-150]
- **Valid Palindrome II** (Easy) [LeetCode](https://leetcode.com/problems/valid-palindrome-ii/) [Coding-Patterns]
- **Maximum Length of Pair Chain** (Medium) [LeetCode](https://leetcode.com/problems/maximum-length-of-pair-chain/) [Coding-Patterns]
- **Minimum Add to Make Parentheses Valid** (Medium) [LeetCode](https://leetcode.com/problems/minimum-add-to-make-parentheses-valid/) [Coding-Patterns]
- **Remove Duplicate Letters** (Medium) [LeetCode](https://leetcode.com/problems/remove-duplicate-letters/) [Coding-Patterns]
- **Largest Palindromic Number** (Medium) [LeetCode](https://leetcode.com/problems/largest-palindromic-number/) [Coding-Patterns]

</details>

#### Key Patterns:
- Local optimal choices leading to global optimum
- Interval scheduling and activity selection
- Greedy choice property
- Optimization problems

---

## 📊 **Complete Progress Tracking**

### High ROI Topics (Priority 1) ⭐⭐⭐⭐⭐
- [ ] Arrays & Hashing (Easy) - 8/8 problems completed
- [ ] Two Pointers (Easy) - 5/5 problems completed
- [ ] Sliding Window (Easy) - 5/5 problems completed  
- [ ] Stack & Queue (Easy) - 5/5 problems completed
- [ ] Breadth-First Search (Easy) - 5/5 problems completed
- [ ] Depth-First Search (Medium) - 5/5 problems completed
- [ ] Backtracking (High) - 6/6 problems completed

**High ROI Completion: ___/7 topics (____%)**

### Medium ROI Topics (Priority 2) ⭐⭐⭐
- [ ] Binary Search (Easy) - 5/5 problems completed
- [ ] Heap (Medium) - 5/5 problems completed
- [ ] Intervals (Medium) - 5/5 problems completed
- [ ] Cyclic Sort (Easy) - 5/5 problems completed
- [ ] K-way Merge (Medium) - 3/3 problems completed
- [ ] Dynamic Programming (High) - 5/5 problems completed

**Medium ROI Completion: ___/6 topics (____%)**

### Low ROI Topics (Priority 3) ⭐
- [ ] Linked Lists (Medium) - 7/7 problems completed
- [ ] Bit Manipulation (Easy) - 5/5 problems completed
- [ ] Trie (Medium) - 3/3 problems completed
- [ ] Union Find (Medium) - 2/2 problems completed
- [ ] Math & Geometry (Medium) - 5/5 problems completed
- [ ] Advanced Graphs (High) - 3/3 problems completed
- [ ] Topological Sort (Medium) - 3/3 problems completed
- [ ] String Manipulation (Easy) - 4/4 problems completed
- [ ] Greedy (High) - 5/5 problems completed

**Low ROI Completion: ___/9 topics (____%)**

---

## 🎯 **Final Study Recommendations**

### Time-Based Mastery Paths

#### 🚀 **1-2 Weeks (Emergency Prep)**
**Goal:** Cover highest-impact topics only
- **Days 1-3:** Arrays & Hashing + Two Pointers (8+5 core problems)
- **Days 4-6:** Sliding Window + Stack & Queue (5+5 core problems)
- **Days 7-10:** BFS basics (5 core problems)
- **Expected Coverage:** 50-65% of interview patterns
- **Success Rate:** Good for junior/mid-level positions

#### 📅 **1 Month (Balanced Prep)**  
**Goal:** Master all high ROI topics
- **Week 1:** Arrays & Hashing + Two Pointers (complete)
- **Week 2:** Sliding Window + Stack & Queue (complete)
- **Week 3:** BFS + DFS basics
- **Week 4:** Advanced DFS + Backtracking fundamentals
- **Expected Coverage:** 75-85% of interview patterns
- **Success Rate:** Good for most positions

#### 📚 **2+ Months (Comprehensive Prep)**
**Goal:** Complete mastery including medium and low ROI
- **Month 1:** All High ROI topics (complete mastery)
- **Month 2:** Binary Search + Heap + Intervals + Cyclic Sort + K-way Merge
- **Month 3:** Dynamic Programming + Linked Lists
- **Month 4+:** All Low ROI topics for 100% coverage
- **Expected Coverage:** 95-100% of interview patterns
- **Success Rate:** Excellent for senior positions and FAANG

### 🎖️ **Mastery Milestones**

**Beginner → Intermediate:**
- [ ] Complete all High ROI Easy topics (Arrays, Two Pointers, Sliding Window, Stack & Queue, BFS)
- [ ] Solve 25+ problems across these topics
- [ ] Can recognize patterns quickly

**Intermediate → Advanced:**
- [ ] Complete all High ROI topics including DFS and Backtracking
- [ ] Solve 40+ problems across High ROI topics
- [ ] Can solve medium problems independently

**Advanced → Expert:**
- [ ] Complete High + Medium ROI topics
- [ ] Solve 60+ problems across all covered topics
- [ ] Can tackle hard problems and optimize solutions

---

## 📖 **Source Attribution**

This guide consolidates content from:
- [**Coding Interview Patterns** (28 patterns)](https://github.com/dipjul/Grokking-the-Coding-Interview-Patterns-for-Coding-Questions) - Comprehensive pattern-based approach
- [**NeetCode-150** (18 categories)](https://github.com/dipjul/NeetCode-150) - Curated problem selection
- **AlgoMonster ROI Analysis** - Data-driven prioritization

**Methodology:** Problems were consolidated across sources, duplicates removed, and organized by ROI data to create the most efficient study path possible.

---

## 🔗 **Quick Reference Links**

- [LeetCode](https://leetcode.com/) - Primary practice platform
- [NeetCode YouTube](https://www.youtube.com/c/NeetCode) - Video explanations
- [AlgoMonster](https://algo.monster/) - Pattern-based learning
- [Educative.io](https://www.educative.io/) - Interactive courses

---

**Remember:** Focus on understanding patterns over memorizing solutions. The ROI-based approach ensures you're studying the most impactful topics first. Consistency beats intensity - study regularly and track your progress!

*Good luck with your interviews! 🚀*