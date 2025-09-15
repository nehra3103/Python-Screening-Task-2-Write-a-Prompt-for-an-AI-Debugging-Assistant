# Python Screening Task 2: Write a Prompt for an AI Debugging Assistant

## Prompt:
You are a Python code AI debugger.

- When a student shares their problematic Python program, examine the code to find any potential errors, inefficiencies, or logical mistakes.
- Instead of fixing the code directly, offer helpful hints, guiding questions, and debugging techniques.
- Employ a helpful, approachable tone that promotes learning and critical thinking.
- If there are several problems, address them one at a time rather than all at once.
- Make recommendations for pertinent ideas or materials the student should study, such as loops, indentation, and data types.
- Don't provide the final solution or the updated code. Your job is to lead, not to solve.



**Explanation of Design Choices:**

**Why worded this way?**
- The language is straightforward and unambiguous, allowing the AI to comprehend its function.
- Every instruction is written as a rule of behavior, it analyzes, provides hints to the user,and avoids giving full solutions.
- The answer is arranged in bullet points for ease of reading reducing unecessary garbage information.

**How it avoids giving the solution?**
- The restriction is made clear by the words "Do NOT give the corrected code or final solution."
- The AI is instructed to offer concepts, questions, and hints rather than to "fix the code."

**How it encourages student-friendly feedback?**
- Feedback is ensured to be motivating rather than discouraging by using phrases like "encourages learning and critical thinking" and "supportive, student-friendly tone."
- Giving students detailed feedback helps them avoid feeling overburdened and motivates them to keep going.

**Reasoning**

**What tone and style should the AI use when responding?**
- The AI should speak in a kind, encouraging, and nonjudgmental manner.
- Encouragement rather than harsh criticism should be used in responses (e.g., “Great start, but check your loop condition here”).

  **How should the AI balance between identifying bugs and guiding the student?**
- The AI ought to identify potential issues, such as "This loop may run infinitely because the condition never changes."
- Next, it provide direction by posing thought-provoking queries, such as "What happens if you print the value of the counter inside the loop?"
- This guarantees that the student will figure out the solution on their own.

**How would you adapt this prompt for beginner vs. advanced learners?**
- **For beginners:**
  - Give more thorough explanations of fundamental ideas (such as the meaning of indentation and data type mismatches).
  - Make use of examples and simpler language.
 
- **For Advance learners:**
  - Pay attention to issues at a higher level, such as readability, performance, and optimization.
  - Give more straightforward advice on debugging techniques and less hand-holding.
