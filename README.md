# Parallel List Ranking Algorithms

Due to academic integrity, the project source code and detailed report are private. This public summary outlines the core objectives, challenges, and achievements. Code/reports cannot be shared, even on request.

## Project Overview

This project explores parallel algorithms for the *list ranking* problem, a fundamental operation in parallel computing with applications in graph algorithms and scientific computing. The goal is to efficiently compute the distance (rank) of each node from the head in a singly linked list, leveraging both shared-memory (OpenMP) and GPU (CUDA) parallelism.

## Algorithms Implemented

- **Wyllie's Algorithm:**  
  A classic parallel list ranking algorithm designed for shared-memory architectures. It uses pointer jumping and iterative updates to achieve logarithmic time complexity with sufficient parallel resources.

- **Helman-JaJa Algorithm:**  
  An advanced approach that partitions the list into sublists, processes them in parallel, and then combines results. This method is well-suited for both CPU (OpenMP) and GPU (CUDA) environments, offering improved scalability for large lists.

## Technologies & Skills

- **OpenMP:** Used for parallelizing algorithms on multi-core CPUs.
- **CUDA:** Applied for GPU acceleration of the Helman-JaJa algorithm.
- **C/C++:** Core implementation language.
- **Algorithm Analysis:** Focused on parallel complexity, synchronization, and memory access patterns.

## My Contributions

- Designed and implemented both Wyllie's and Helman-JaJa list ranking algorithms from academic papers.
- Developed parallel solutions using OpenMP and CUDA, optimizing for performance and correctness.
- Analyzed and compared the scalability and efficiency of each approach on large datasets.

## Learning Outcomes

- Gained hands-on experience with parallel programming models (OpenMP, CUDA).
- Deepened understanding of parallel algorithm design, especially for irregular data structures like linked lists.
- Practiced translating theoretical algorithms from research literature into efficient, real-world code.
- Strengthened skills in performance analysis and debugging of parallel applications.
