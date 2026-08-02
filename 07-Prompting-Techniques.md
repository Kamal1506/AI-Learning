# 🎯 Prompting Techniques

## 📖 Definition

**Prompting Techniques** are different ways of writing prompts to help AI generate more accurate, relevant, and consistent responses.

Different tasks require different prompting techniques.

---

## 🤔 Why Do Prompting Techniques Exist?

Sometimes, simply giving an instruction is enough.

Other times, AI performs better when you provide examples or ask it to reason step by step.

### 🌍 Real-World Example

Suppose you ask someone:

> Solve this Java problem.

They may ask:

- Which Java version?
- What is the input?
- What is the expected output?
- Are there any constraints?

Now imagine you first show them one solved example.

The next problem becomes much easier to solve.

AI behaves similarly.

Sometimes you don't just tell it what to do—you also show it examples.

---

# 🧩 Types of Prompting Techniques

```text
Prompt Engineering
│
├── Zero-shot Prompting
├── One-shot Prompting
├── Few-shot Prompting
└── Chain-of-Thought (CoT) Prompting
```

---

# 1️⃣ Zero-shot Prompting

## 📖 Definition

**Zero-shot Prompting** means giving the AI only an instruction without providing any examples.

The model performs the task based solely on the prompt.

### Example

```text
Translate this into French.

Good Morning.
```

No example is provided.

This is **Zero-shot Prompting**.

Another example:

```text
Explain polymorphism.
```

Again, no examples.

---

## 🌍 Real-World Analogy

A teacher says:

> Write an essay about pollution.

She does **not** show any sample essay.

You simply write it.

This is Zero-shot Prompting.

---

## ✅ Best Used For

- Summarizing text
- Translation
- Explaining concepts
- Answering factual questions
- Generating code

---

## 💼 Interview Definition

> Zero-shot Prompting is a prompting technique where the AI performs a task using only the instruction, without being provided any examples.

---

# 2️⃣ One-shot Prompting

## 📖 Definition

**One-shot Prompting** provides **one example** before asking the AI to perform a similar task.

### Example

```text
Question:
2 + 2

Answer:
4

Now solve:

7 + 5
```

One example is given.

Hence, **One-shot Prompting**.

Another example:

```text
Input:
Apple

Output:
Fruit

Now classify:

Carrot
```

The AI learns the pattern from a single example.

---

## 🌍 Real-World Analogy

A teacher solves **one** math problem.

Then asks you to solve another.

---

## 💼 Interview Definition

> One-shot Prompting is a technique where one example is provided before asking the AI to perform a similar task.

---

# 3️⃣ Few-shot Prompting

## 📖 Definition

**Few-shot Prompting** provides **multiple examples** before asking the AI to solve a new task.

### Example

```text
Positive → Happy

Negative → Sad

Fast → Slow

Now answer:

Hot →
```

Another example:

```text
Input:
5

Output:
25

Input:
8

Output:
64

Input:
10

Output:
?
```

The AI learns the pattern from several examples.

---

## 🌍 Real-World Analogy

A teacher solves:

- Problem 1
- Problem 2
- Problem 3

Then asks you to solve Problem 4.

---

## 💼 Interview Definition

> Few-shot Prompting provides multiple examples to help the AI understand the expected pattern before solving a new task.

---

# 📊 Zero-shot vs One-shot vs Few-shot

| Technique | Examples Given |
|-----------|----------------|
| Zero-shot | 0 |
| One-shot | 1 |
| Few-shot | 2 or More |

---

# 4️⃣ Chain-of-Thought (CoT) Prompting

## 📖 Definition

**Chain-of-Thought (CoT) Prompting** encourages the AI to reason through intermediate steps before producing the final answer.

Instead of asking only for the final answer, we ask the AI to think step by step.

### Example

Instead of:

```text
Solve this math problem.
```

Ask:

```text
Solve this math problem step by step and explain your reasoning.
```

---

## 🌍 Real-World Example

Question:

```text
24 × 15
```

Instead of immediately answering:

```text
360
```

The reasoning is:

```text
24 × 10 = 240

24 × 5 = 120

240 + 120 = 360
```

This is Chain-of-Thought Prompting.

---

## ✅ Best Used For

- Mathematics
- Logical Reasoning
- Coding Problems
- Algorithm Design
- Debugging
- Multi-step Problems

---

## ❌ Not Usually Needed For

- Translation
- Simple Definitions
- Basic Summaries

---

## 💼 Interview Definition

> Chain-of-Thought Prompting is a technique that encourages the AI to reason through intermediate steps before producing the final answer, improving performance on complex reasoning tasks.

---

# 💻 GitHub Copilot Examples

### Zero-shot

```text
Write a Binary Search program in Java.
```

---

### One-shot

```text
Example:

Linear Search

Now write Binary Search.
```

---

### Few-shot

```text
Example 1:
Bubble Sort

Example 2:
Selection Sort

Now generate Insertion Sort.
```

---

### Chain-of-Thought

```text
Explain how Binary Search works step by step before writing the Java implementation.
```

---

# 📋 Comparison Table

| Technique | Examples | Best Used For |
|-----------|----------|---------------|
| Zero-shot | None | Simple tasks |
| One-shot | One | Learning from a single example |
| Few-shot | Multiple | Improving consistency and formatting |
| Chain-of-Thought | Step-by-step reasoning | Complex reasoning and problem solving |

---

# 💼 Interview Questions

## ❓ What is Zero-shot Prompting?

> Zero-shot Prompting is giving the AI only an instruction without providing any examples.

---

## ❓ What is One-shot Prompting?

> One-shot Prompting provides one example before asking the AI to perform a similar task.

---

## ❓ What is Few-shot Prompting?

> Few-shot Prompting provides multiple examples so the AI can understand the expected pattern before solving a new task.

---

## ❓ What is Chain-of-Thought Prompting?

> Chain-of-Thought Prompting encourages the AI to reason through intermediate steps before producing the final answer.

---

# ❓ Common Interview Questions

### Q1. Which prompting technique uses no examples?

**Answer:** Zero-shot Prompting.

---

### Q2. Which prompting technique uses one example?

**Answer:** One-shot Prompting.

---

### Q3. Which prompting technique uses multiple examples?

**Answer:** Few-shot Prompting.

---

### Q4. Which prompting technique is best for solving complex reasoning problems?

**Answer:** Chain-of-Thought Prompting.

---

### Q5. Which prompting technique is best for simple tasks like translation or summarization?

**Answer:** Zero-shot Prompting.

---

# 🧠 Memory Trick

```text
Zero-shot  → 0 Examples

One-shot   → 1 Example

Few-shot   → 2+ Examples

Chain-of-Thought → Think Step by Step
```

---

## 📌 Key Takeaways

- Prompting techniques improve AI responses.
- **Zero-shot** uses no examples.
- **One-shot** uses one example.
- **Few-shot** uses multiple examples.
- **Chain-of-Thought** encourages step-by-step reasoning.
- Choosing the right prompting technique helps generate more accurate and useful outputs.
