# 💬 What is Prompt Engineering?

## 📖 Definition

**Prompt Engineering** is the process of designing and refining prompts to obtain accurate, relevant, and high-quality responses from an AI model.

### Simple Definition

A **Prompt** is simply the input or instruction you give to an AI.

Prompt Engineering is the skill of asking AI the right way.

---

## 🎯 Why is Prompt Engineering Important?

The quality of an AI's response depends heavily on the quality of the prompt.

> **Same AI + Different Prompt = Completely Different Answer**

---

## 🌍 Real-World Example

Suppose three people ask ChatGPT to write Java code.

### 👤 Person 1

```text
Write Java code.
```

---

### 👤 Person 2

```text
Write a Java program to reverse a string.
```

---

### 👤 Person 3

```text
You are a senior Java developer.

Write a Java 17 program to reverse a string without using the built-in reverse() method.

Explain the algorithm.

Mention the time complexity.

Use meaningful variable names.

Add comments.

Provide JUnit test cases.
```

### ✅ Who Gets the Best Answer?

**Person 3**

Did ChatGPT become smarter?

**No.**

The **prompt became better.**

---

# ❓ What is a Prompt?

A **Prompt** is the input or instruction given to an AI model that guides it to generate the desired response.

### Simple Definition

A prompt is simply **what you ask the AI.**

---

## 🌍 Real-World Analogy

Imagine asking someone for directions.

### ❌ Bad Prompt

```text
Help me.
```

The person will ask:

- Help with what?

---

### ✅ Better Prompt

```text
How do I reach Chennai Central Railway Station from Chennai Airport?
```

Now the person knows exactly what you need.

AI works the same way.

---

# 🚀 Why Does Prompt Engineering Exist?

AI is **not** a mind reader.

It only knows what you tell it.

If your instructions are vague,

the output will also be vague.

### 📌 Famous Computer Science Principle

> **Garbage In, Garbage Out (GIGO)**

If your input is poor,

don't expect high-quality output.

Prompt Engineering helps AI understand exactly what you want.

---

# 🧩 Anatomy of a Good Prompt

A good prompt usually contains:

```text
Role
   ↓
Task
   ↓
Context
   ↓
Constraints
   ↓
Output Format
```

---

## 👤 1. Role

Tell AI who it should act as.

### Examples

- You are a Java Developer.
- You are an HR Interviewer.
- You are a Spring Boot Expert.
- You are my coding mentor.

The role changes the style and depth of the response.

---

## ✅ 2. Task

Clearly explain what you want.

### ❌ Instead of

```text
Explain Java.
```

### ✅ Better

```text
Explain the Java Collections Framework.
```

### ⭐ Even Better

```text
Explain the Java Collections Framework for a fresher preparing for technical interviews.
```

---

## 📚 3. Context

Provide background information.

### Example

```text
I know Java basics.

I don't know multithreading.

Teach me step by step.
```

The AI now understands your current knowledge level.

---

## 📏 4. Constraints

Specify your requirements.

### Examples

- Keep the explanation under 200 words.
- Use simple English.
- Give one real-world example.
- Use Java 17.
- Don't use recursion.

Constraints help shape the response.

---

## 📄 5. Output Format

Tell AI how you want the answer.

Examples:

- Bullet Points
- Table Format
- Markdown
- Interview Answer
- Code Only
- Step-by-Step Explanation

This reduces the need for follow-up requests.

---

# ⚖️ Bad Prompt vs Good Prompt

## ❌ Bad Prompt

```text
Explain Java.
```

Very broad.

---

## ✅ Better Prompt

```text
Explain Java Collections Framework with real-world examples.
```

---

## ⭐ Excellent Prompt

```text
You are a Java trainer.

Explain the Java Collections Framework for a fresher preparing for interviews.

Use simple English.

Give real-world examples.

Provide a comparison table.

Ask me three interview questions at the end.
```

The more specific the prompt, the better the response.

---

# 📌 One Important Rule

AI can only use:

- The information you provide
- What it learned during training
- Additional tools or documents, if available

If you leave out important details,

the AI must make assumptions.

Better prompts reduce assumptions and improve accuracy.

---

# 💻 Prompt Engineering in GitHub Copilot

### ❌ Basic Prompt

```text
Create unit test.
```

Copilot may generate a basic test.

---

### ✅ Better Prompt

```text
Generate JUnit 5 test cases for this Spring Boot service.

Cover both success and failure scenarios.

Use Mockito.

Follow the Arrange-Act-Assert (AAA) pattern.

Target 90%+ code coverage.
```

The second prompt provides much clearer instructions, resulting in a more useful output.

---

# 💼 Interview Questions

## ❓ What is a Prompt?

> A prompt is the input or instruction provided to an AI model that guides it in generating the desired response.

---

## ❓ What is Prompt Engineering?

> Prompt Engineering is the process of creating and refining prompts to obtain accurate, relevant, and high-quality outputs from AI models.

---

## ❓ Why is Prompt Engineering Important?

> Prompt Engineering is important because the quality of an AI's response largely depends on the quality of the prompt. Clear, specific, and well-structured prompts help generate more accurate, relevant, and useful outputs.

---

# ❓ Common Interview Questions

### Q1. What is a Prompt?

**Answer:** A prompt is the input or instruction given to an AI model to guide its response.

---

### Q2. What is Prompt Engineering?

**Answer:** Prompt Engineering is the process of designing effective prompts to generate accurate and high-quality responses from AI models.

---

### Q3. Why is Prompt Engineering important?

**Answer:** Because better prompts produce better outputs by reducing ambiguity and helping the AI understand the user's intent.

---

### Q4. What are the five parts of a good prompt?

**Answer:**

- Role
- Task
- Context
- Constraints
- Output Format

---

### Q5. What does GIGO mean?

**Answer:** **Garbage In, Garbage Out.** Poor-quality prompts usually lead to poor-quality AI responses.

---

## 📌 Key Takeaways

- A **Prompt** is the instruction given to an AI.
- **Prompt Engineering** is the skill of writing effective prompts.
- Better prompts produce better responses.
- A good prompt usually includes:
  - 👤 Role
  - ✅ Task
  - 📚 Context
  - 📏 Constraints
  - 📄 Output Format
- Clear and specific prompts reduce ambiguity and improve AI-generated results.
