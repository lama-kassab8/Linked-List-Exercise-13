# LeetCode 24 - Swap Nodes in Pairs

## Problem Statement

Given a linked list, swap every two adjacent nodes and return its head.

You must solve the problem **without modifying the values in the list's nodes** (i.e., only nodes themselves may be changed).

### Example:
Input: head = [1,2,3,4]
Output: [2,1,4,3]

## Constraints

- The number of nodes in the list is in the range `[0, 100]`.
- `0 <= Node.val <= 100`

## Approach

We need to swap every pair of adjacent nodes by changing pointers, not values.

### Possible Approaches:

- **Iterative approach:**
  - Use a dummy node to simplify edge cases.
  - Loop through the list and swap nodes pair by pair using pointer manipulation.

- **Recursive approach:**
  - Base case: if the list has 0 or 1 node, return it.
  - Recursively swap the next pairs and re-link the nodes.

## Edge Cases

- Empty list → return `None`
- Single node → no swap, return the node as is

---

## Status

In progress 
