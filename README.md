## LRU Cache Simulator

An interactive project that demonstrates the **Least Recently Used (LRU)** cache replacement algorithm using both:

- A **C++ console implementation**
- A modern **HTML/CSS/JavaScript visualization website**

This project helps visualize how cache memory works by tracking cache hits, misses, and evictions in real time.

---

# Project Overview

The project contains two versions of the simulator:

## 1. C++ Console Simulator

The C++ program simulates how an LRU cache behaves internally.

Features:
- Cache hit/miss detection
- LRU eviction handling
- Cache state printing
- Hit rate calculation
- Input validation

The console version focuses on the algorithm and memory management logic.

---

## 2. Interactive Web Visualization

The HTML website provides a visual and interactive representation of the LRU algorithm.

Features:
- Animated cache visualization
- Step-by-step execution
- Full simulation mode
- Live statistics
- Preset memory patterns
- Modern responsive UI
- Real-time cache state updates

The website helps users understand how LRU works visually.

---

# Technologies Used

## Backend Logic
- C++

## Frontend Visualization
- HTML5
- CSS3
- JavaScript

---

# How the LRU Algorithm Works

The Least Recently Used (LRU) algorithm removes the item that has not been accessed for the longest amount of time.

### Process:
1. The memory address is accessed
2. If address exists in cache → HIT
3. If the address does not exist → MISS
4. Most recently used item moves to the back
5. The least recently used item is removed when the cache is full

---

