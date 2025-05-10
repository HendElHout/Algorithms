# Sorting Algorithms – Design, Implementation, and Complexity Analysis

This project implements and analyzes three fundamental sorting algorithms: **Quick Sort**, **Merge Sort**, and **Insertion Sort**. It explores their performance across different input scenarios and examines time complexity, space usage, and algorithm stability.

## 📌 Project Overview

The objective of this project is to:

- Implement three sorting algorithms in Python.
- Analyze their performance in terms of time and space complexity.
- Compare their efficiency on various input types (random, sorted, reversed).
- Visualize and interpret performance results through graphs.

## 🚀 Learning Goals

- Understand how divide-and-conquer algorithms like Quick Sort and Merge Sort operate.
- Learn to analyze algorithm complexity in best, average, and worst-case scenarios.
- Develop modular and maintainable Python code for algorithmic problems.

## 🧠 Algorithms Implemented

### 1. Insertion Sort
- **Best Case:** O(n) – Already sorted.
- **Average Case:** O(n²)
- **Worst Case:** O(n²) – Reverse sorted.
- ✅ Stable | ✅ In-place | 🔁 Incremental

### 2. Merge Sort
- **Best/Average/Worst Case:** O(n log n)
- ✅ Stable | ❌ In-place | ⚙️ Divide & Conquer

### 3. Quick Sort
- **Best/Average Case:** O(n log n)
- **Worst Case:** O(n²) – Already sorted.
- ❌ Stable | ✅ In-place | ⚙️ Divide & Conquer

## 📊 Time Complexity Summary

| Algorithm      | Best Case   | Average Case | Worst Case |
|----------------|-------------|--------------|------------|
| Quick Sort     | O(n log n)  | O(n log n)   | O(n²)      |
| Merge Sort     | O(n log n)  | O(n log n)   | O(n log n) |
| Insertion Sort | O(n)        | O(n²)        | O(n²)      |

## 📈 Performance Insights

| Input Type | Fastest Algorithm     | Notes                              |
|------------|-----------------------|------------------------------------|
| Random     | Quick Sort / Merge Sort | Quick Sort slightly faster         |
| Sorted     | Insertion Sort         | Performs in linear time            |
| Reversed   | Merge Sort             | Insertion Sort performs worst here |

## 🛠️ Deliverables

- Python scripts for each sorting algorithm.
- A detailed report including:
  - Code documentation
  - Test cases for various input types
  - Performance graphs
  - Time complexity tables

## 🧪 Performance Testing

Test case generation for:
- Random arrays
- Sorted arrays
- Reversed arrays

Performance is measured by:
- Execution time across different input sizes
- Visualization using graphs

## 📌 Conclusion

- **Insertion Sort** is optimal for small or nearly sorted datasets.
- **Merge Sort** guarantees stable and consistent performance.
- **Quick Sort** is typically fastest but needs careful pivot selection.

## 👤 Author

**Hend Elhout**  
ID: 192300146

---

> 📁 Note: All code and analysis are available in this repository.
