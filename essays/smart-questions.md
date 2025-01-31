---
layout: essay
type: essay
title: "Smart Questions, Good Answers"
# All dates must be YYYY-MM-DD format!
date: 2015-09-08
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/smart-questions/rtfm.png">

Asking questions the "smart" way is an important skill for software engineers because it helps us get better and faster answers. Eric Raymond explains how being clear, doing research beforehand, and providing enough details can make a big difference when asking technical questions. On Stack Overflow, well-asked questions tend to get useful responses, while unclear or lazy questions might get ignored or even downvoted. To understand this better, I looked at two Stack Overflow questions—one that was well-structured and one that wasn’t.

The "smart" question followed Raymond’s advice by including clear details, showing what the person already tried, and explaining exactly what the problem was. For example, a user asked about why certain random strings produce colors when used as a background in HTML. They included code examples and explained their thought process, which helped others understand the issue quickly. As a result, the responses were insightful and directly answered the question. This question received upvotes, showing that it was a good example of how to ask effective questions.

### Example of a Smart Question:
**Question:** "Why is my Python function returning None instead of the expected value?"

```python
# I am trying to return the square of a number, but my function prints None. What am I doing wrong?
def square(num):
    print(num * num)  # I expect this to return a value

result = square(5)
print(result)  # Expected output: 25, but I get None instead
```

**Why this is smart:** The question includes a clear explanation of the issue, a code example, expected output, and what was observed instead. This allows others to quickly identify the issue (missing `return` statement) and provide a useful answer.

### Example of a Not Smart Question:
**Question:** "My Python code is broken. Help?"

```python
def something():
    x = 10
    y = 20
    z = x + y
```

**Why this is not smart:** The question lacks context, details, expected output, or even an error message. It doesn't explain what the user is trying to achieve or what issue they are facing, making it difficult for others to provide meaningful help.

On the other hand, the "not smart" question lacked context and clarity. An example of this is a question like, "use ternary relationship or complex attribute?" without any background on the project, the problem they were trying to solve, or the design methods they were considering. The responses were mostly requests for clarification, and the question was eventually closed. This highlights how vague questions often lead to confusion, more follow-up questions, and less productivity.

From this exercise, I realized that asking smart questions leads to better help and a more positive experience on Stack Overflow. When people take the time to structure their questions clearly, they get better responses and learn more in the process. This experience made me more aware of how important communication is in programming and how small improvements in how we ask for help can make a big difference.

