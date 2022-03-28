# Introduction to xprocket

## What is a xprocket?

xprocket is a closed-end question-and-answer widget, like the one below:

<xprocket-element>
id: testing
mode: mc
concept:
  question: 
  - What is xprocket?
  answer:
  - A question-and-answer widget.
  - A tool for presenting closed-ended questions.
  foil:
  - 
    - A clock-and-weather widget.
    - A frequently-asked-questions widget. 
    - A tool for presenting open-ended questions.
  error:
  - 
    - The combustion mechanism in a car engine.
    - text: Magical digital technology.
      rationale: You're not entirely wrong! But the correct answer precisely defines what a xprocket is for and what it does. Try again.
    - text: Another learning management system. 
      rationale: xprocket is not an LMS; it simply displays lesson content and does not provide any out-of-the-box student management tools. Think of it like a Gameboy but for learning -- you can plug in your lesson, save your progress locally. That's it.
  hint: Read the text above to find the answer.
</xprocket-element>

Notice that the xprocket will provide you with instant feedback, and changes it's own presentation each time you interact with it. This is possible because the original author of this current lesson provided a list of all the information the xprocket needed to know: a series of similar questions on a specific topic, and corresponding answers, foils (one of which will always appear in the array), errors, and hints. Packaged together, that information helps your audience understand the concept you are trying to teach. Here's the exact text used for the above xprocket:

```
id: testing
mode: mc
concept:
  question: 
  - What is xprocket?
  answer:
  - A question-and-answer widget.
  - A tool for presenting closed-ended questions.
  foil:
  - 
    - A clock-and-weather widget.
    - A frequently-asked-questions widget. 
    - A tool for presenting open-ended questions.
  error:
  - 
    - The combustion mechanism in a car engine.
    - text: Magical digital technology.
      rationale: You're not entirely wrong! But the correct answer precisely defines what a xprocket is for and what it does. Try again.
    - text: Another learning management system. 
      rationale: xprocket is not an LMS; it simply displays lesson content and does not provide any out-of-the-box student management tools. Think of it like a Gameboy but for learning -- you can plug in your lesson, save your progress locally. That's it.
  hint: Read the text above to find the answer.
```
