# Python Screening Task 2: Write a Prompt for an AI Debugging Assistant
## The Prompt

```plaintext
Role: You are CodeGuide, a supportive and patient Python programming tutor. Your primary goal is to help students learn debugging skills, not to provide direct answers.

Core Instructions:

1.  Strict Rule: Never provide the corrected code, a full solution, or copy-pastable code blocks.
2.  First Step: Always begin by asking the student: "What did you expect your code to do, and what is it actually doing instead?"
3.  Teaching Method: Ask them easy questions about how their code works, what the variables do, and how the steps in their code flow. 
4.  Feedback Style:
    - Provide Hints, Not Answers: Point toward the type of error (e.g., "Check loop boundaries," "Review indentation here").
    - Suggest Strategies: Recommend using `print()` statements to trace values or isolating code sections to test.
    - Be Encouraging: Use a positive tone. Say things like "You're on the right track!" and "Debugging is a core skill!"
5.  Adaptation: Tailor your response:
    - Beginners: Offer foundational explanations and simpler hints.
    - Advanced Students: Use technical language and focus on higher-level concepts.`
```
---
### Why you worded it the way you did?
I chose clear, direct phrases like “analyze,” “offer suggestions,” and “don’t give away the solution” because I want the AI to act as a helpful teacher, not just a code fixer. By asking the AI to be friendly and supportive, the prompt encourages a positive learning experience, helping students feel confident in their ability to solve problems. Starting with a question about expectations helps both the student and the AI pinpoint what went wrong, making the feedback truly meaningful.

### How you ensured it avoids giving the solution?
Throughout the prompt, I emphasized that the AI must not share the correct code or any copy-pastable answers. Instead, it asks the AI to give hints and ask questions, so the student is guided gently toward the answer rather than just handed it. By focusing on clues and strategic suggestions rather than direct instructions, students are encouraged to engage with their code and practice the problem-solving process themselves.

### How it encourages helpful, student-friendly feedback?
The prompt tells the AI to be supportive, positive, and constructive in every message. By giving the AI methods to offer hints, ask guiding questions, and suggest common debugging strategies (like using print() statements), the student learns how to look for bugs in a systematic way. This approach also puts the responsibility on the student to think through their mistakes, which helps them build real confidence and independence as a programmer.

---
## Required Reasoning Answers

### What tone and style should the AI use when responding?
The AI should sound like a kind, encouraging tutor—never critical or harsh. Every reply should feel welcoming and patient, using simple language when needed. The goal is to keep the student motivated, even if they’re stuck, by showing empathy and celebrating their effort.

### How should the AI balance between identifying bugs and guiding the student? 
The AI should first point out where it sees a bug or something that might be confusing, but then it should gently ask the student what they think or suggest small steps for checking or fixing the problem. It should provide enough detail so the student knows where to look, but always make the student feel like they are discovering the answer themselves.

### How would you adapt this prompt for beginner vs. advanced learners?
For beginners, the AI should use simple words, break explanations into small steps, and explain basic Python ideas clearly. If a student seems more experienced, the AI can use more technical language, discuss alternative approaches, and reference advanced debugging tools or strategies. Always match the feedback to the student’s comfort level—making sure it's both understandable and helpful.
***

## Checklist

- [x] Prompt is clear, specific, and well-structured
- [x] Reasoning is thoughtful and well-articulated
- [x] Required reasoning answers are present

***
