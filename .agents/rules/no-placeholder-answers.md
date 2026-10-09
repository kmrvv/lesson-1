# Rule: Do Not Put Answers In Placeholders

When creating interactive educational exercises, quizzes, fill-in-the-blanks, or spelling inputs in HTML:
- **NEVER** put the correct answer, partial solution, or answer spoil in the `placeholder` attribute of an `<input>` or `<textarea>`.
- Placeholder text is visible to students before they type, which spoils the answer and defeats the purpose of the exercise.
- Use generic placeholders such as `placeholder="..."`, `placeholder="Type here..."`, `placeholder="Write word"`, `placeholder="?"`, or leave the placeholder empty.
- Keep the correct answer strictly in `data-ans` attributes or JavaScript state/verification logic.
