# Contributing

This project gets more useful when feedback is reproducible, not just “this felt better.”

## Report an evaluation

Use the **Benchmark or A/B result** issue form and include, where possible:

- the exact model or snapshot and the date tested;
- the ChatGPT plan or API setup;
- the instruction variant and an empty-instructions baseline;
- reasoning effort, temperature, tools, and other relevant settings;
- the task set, sample size, and scoring method;
- raw inputs and outputs, or a shareable subset;
- limitations, failed cases, and anything that could bias the result.

Negative and mixed results are useful. Please do not turn a small anecdotal test into a broad performance claim.

## Suggest a prompt change

Use the **Prompt change** issue form. Describe the failure mode first, then propose the smallest wording change that could address it. Include an example and note what the change might make worse.

## Pull requests

Keep pull requests focused and easy to review.

- Preserve the project history and upstream attribution.
- Keep the published prompts general-purpose; do not add contributor-specific preferences or account details.
- Recalculate stated character counts when a prompt changes.
- Prefer primary sources for current product behavior and limits.
- Do not claim an improvement without a comparable result or clearly label the claim as a hypothesis.

