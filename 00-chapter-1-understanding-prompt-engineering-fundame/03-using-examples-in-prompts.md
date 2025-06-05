---
position: 3
title: Using Examples In Prompts
---

## Using Examples in Prompts:

Providing examples of input and output content and format is helpful for the model, especially when the model may lack training on your request or use case. Helping the model with examples is also known as few-shot Prompting.

Choose examples that are relevant, high-quality, and written. Even minor errors can mislead the model. To build robust outputs, include diverse cases—especially instances of edge (inputs that are unusual or unexpected) the model should learn to handle.



"Well-crafted prompts lead to more accurate, relevant..." — Google Cloud.





Pro Tip: Word Choice

Using action verbs like "Act as," "Summarize," "Compare," and "Generate" sets expectations.





Here are a few examples taken from [Google’s Guide to Prompting](https://grow.google/enroll-certificates/prompting-essentials-mid/):

Act, Analyze, Categorize, Classify, Contrast, Compare, Create, Describe, Define, Evaluate, Extract, Find, Generate, Identify, List, Measure, Organize, Parse, Pick, Predict, Provide, Rank, Recommend, Return, Retrieve, Rewrite, Select, Show, Sort, Summarize, Translate, Write.



Pro Tip: Output Format

For example, limit the length of the answer or structure the answer in a specific way, such as a table or JSON format. Generally, instructions are better than constraints for Prompting. Examples: "Explain quantum physics in one sentence."





Pro Tip: Role-based Prompting

Role prompting is a technique in prompt engineering that involves assigning a specific role to the large language model. This helps the model generate more relevant and informative output, as it can craft responses tailored to the particular role it has been assigned.

For example, you could role-prompt a gen AI model to be a travel agent, coach, or motivational speaker.





Pro Tip: Ask AI for help by Asking clarifying questions.

If you're unsure how to frame your problem or question, ask the AI to help by posing clarifying questions. Add something like this to the end of your prompt.

"Before proceeding, ask any clarifying questions you need."



It can interview you, gather your preferences, and even draft a better prompt—along with an explanation of why it's an improvement. Ultimately, you have the final say on how the prompt is shaped.