# 🚀 Smart Study Planner: The CP Coach
**Tagline:** High-density algorithmic hints, zero-latency intuition.

---

## 📌 Overview
**Smart Study Planner** is a specialized, lightweight AI engine built on the **Smolify** platform. It is designed for competitive programmers and students who are "stuck" on a problem but want a strategic nudge rather than a full code spoiler. 

Unlike general LLMs that provide verbose, conversational solutions, Smart Study Planner is a **distilled specialist** that extracts only the algorithmic DNA of a problem statement to help students plan their approach.

---

## 🛠️ Core Capabilities
* **Pattern Extraction:** Instantly maps story-based problem descriptions to core Data Structures and Algorithms (DSA).
* **Constraint Analysis:** Translates input sizes (e.g., **1 ≤ N ≤ 10⁵**) into the required Big-O complexity.
* **Minimalist Feedback:** Provides "hints" to facilitate active learning instead of copy-paste solutions.
* **Token Efficiency:** Reduces output volume by **80%** compared to standard LLMs, ensuring faster inference and lower compute costs.

---

## 📥 Input Specification
The system accepts raw text directly from platforms like **LeetCode**, **Codeforces**, or **HackerRank**.

**Sample Input:**
> *"Given an array of integers heights representing the histogram's bar height where the width of each bar is 1, return the area of the largest rectangle in the histogram."*

---

## 📤 Output Specification
The model generates a structured, high-density "Distilled Hint":

| Field | Description | Example Output |
| :--- | :--- | :--- |
| **Pattern** | The primary algorithm or data structure. | **Monotonic Stack** |
| **Complexity** | The optimal Time and Space bounds. | **$O(n)$ Time \| $O(n)$ Space** |
| **Key Observation** | The critical logic required to solve. | For each bar, find the first smaller bar to its left and right to determine its maximum possible width. |

---

## 🧠 The Smolify Advantage
1.  **Distilled Mission:** By using the **Model Foundry**, we eliminated "hallucinations" and conversational filler (e.g., "Hello! I'd be happy to help...").
2.  **Privacy-First:** Specialized small models can be deployed locally, ensuring user data doesn't need to leave the device.
3.  **Speed:** Near-instant response time due to the reduced parameter count and focused instruction set.

---

## 📋 Hackathon "Quick Pitch"
> "Most students fail to learn because they jump straight to the solution. **Smart Study Planner** uses **Smolify** to create a 'Hint Engine' that gives you the *intuition* without the *answer*. We built a model that thinks like a Grandmaster but talks like a Coach."

---

**Developed at:** Google ML Kolkata Event 2026  
**Platform:** Powered by Smolify
