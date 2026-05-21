# Using AI tools in research training

AI tools can be useful research assistants when they are used carefully. They can help you summarize difficult material, organize your thoughts, debug code, generate study questions, and turn a vague idea into a more concrete research plan.

However, AI tools should not replace careful reading, source checking, or your own reasoning. A good researcher uses AI to support the research process, not to avoid the research process.

## What AI tools are good for

AI tools are most useful when you give them a specific task and enough context to work from. In research training, they can help you:

- summarize a paper, textbook section, or research log,
- explain unfamiliar terminology,
- identify the main assumptions in a model,
- generate questions to ask while reading,
- organize notes into a clearer structure,
- suggest next steps for a project,
- help debug Python code,
- compare different interpretations of a result,
- create a checklist for a research task.

A useful rule is this: use AI tools to make your thinking more organized, not to replace your thinking.

## Good prompt engineering

A prompt is the instruction you give to an AI tool. Better prompts usually produce better responses. A strong research prompt usually includes four parts:

1. **Context** — what you are working on.
2. **Task** — what you want the AI to do.
3. **Constraints** — what the AI should or should not include.
4. **Output format** — how you want the answer organized.

For example, instead of writing:

> Explain this paper.

write something more specific:

> I am an undergraduate beginning a research project on planets in binary star systems. Summarize this paper in plain language. Focus on the research question, physical model, main assumptions, key results, and what I should understand before trying to reproduce the calculation. End with five questions I should ask my research advisor.

The second prompt is better because it gives the AI a role, audience, purpose, and structure.

## A useful prompt template

When you are unsure how to begin, use a prompt like this:

> I am working on [topic or task]. My current goal is [specific goal]. I already know [background knowledge]. I am confused about [specific issue]. Please help me by [task]. Organize the response as [desired format]. Do not assume more advanced background than [level].

For coding tasks, include the code, the error message, and what you expected to happen:

> I am running this Python code to [goal]. I expected [expected result], but I got [actual result or error message]. Explain what the error means, identify the most likely problem, and suggest a minimal fix. Do not rewrite the entire notebook unless necessary.

## Prompt, iterate, revise

Using AI well is usually not a one-step process. A better workflow is:

1. **Prompt** — ask for a first explanation, summary, plan, or diagnosis.
2. **Evaluate** — check whether the response is useful, correct, and specific.
3. **Iterate** — ask follow-up questions or request a different format.
4. **Revise** — update your notes, code, research plan, or explanation using what you learned.
5. **Verify** — check the result against the original source, your data, or a reliable reference.

For example, you might first ask for a summary of a paper. Then you might ask for the assumptions behind the model. Then you might ask how those assumptions relate to your own project. Finally, you should return to the paper and verify that the AI's explanation matches what the authors actually wrote.

## Using NotebookLM

[NotebookLM](https://notebooklm.google/) is especially useful when you want to work with a specific set of sources. You can upload papers, notes, reports, or other documents, then ask questions about those sources.

This makes NotebookLM useful for:

- summarizing a research paper,
- comparing several papers,
- asking questions about a textbook chapter,
- generating a study guide from uploaded notes,
- creating a briefing document for a new research topic,
- finding where a concept appears in your uploaded sources.

One of the most useful features is the ability to ask source-grounded questions. For example:

> Based only on the uploaded sources, what are the main assumptions used in this model?

or

> Which source discusses the stability boundary for circumbinary planets? Give the answer with citations to the uploaded material.

NotebookLM can also generate audio overviews. These can be useful before reading a difficult paper because they give you a first-pass explanation of the main ideas. However, an audio overview should be treated as a starting point, not as a replacement for reading the paper.

A good workflow is:

1. Upload the paper or notes.
2. Generate a short summary or audio overview.
3. Ask for the main research question, methods, assumptions, and conclusions.
4. Read the original source yourself.
5. Ask follow-up questions about confusing sections.
6. Write your own summary in your research log.

## Using Illuminate

[Illuminate](https://illuminate.google.com/) is another AI tool that can help flatten the learning curve for complex research papers. It is designed to turn research papers into AI-generated audio summaries.

This can be useful when you are encountering a paper for the first time. Listening to an AI-generated discussion can help you identify the topic, main result, and important vocabulary before doing a careful reading.

Illuminate is most useful for:

- getting a first-pass overview of a paper,
- preparing to read a dense technical article,
- reviewing a paper while commuting or doing routine tasks,
- identifying which parts of a paper deserve closer attention.

However, it should not be used as your only interaction with a paper. Audio summaries can miss details, simplify assumptions, or overemphasize some parts of the paper. After using Illuminate, you should still read the abstract, introduction, figures, methods, and conclusions yourself.

## Trust, but verify

AI tools can sound confident even when they are wrong. They can misunderstand a source, invent details, give incomplete explanations, or produce code that runs but does not answer the right question.

For that reason, every AI-assisted result should be checked.

When using AI in research, verify:

- **claims** against the original paper or textbook,
- **citations** by opening the actual source,
- **equations** by checking units, limits, and assumptions,
- **code** by running simple test cases,
- **summaries** by comparing them to the original source,
- **research plans** by discussing them with your advisor or instructor.

A good habit is to ask:

> What would I need to check before trusting this answer?

You can also ask the AI tool itself:

> List the parts of your answer that I should verify against the original source.

This does not guarantee correctness, but it helps you identify what needs checking.

## From a vague idea to a research plan

AI tools can be especially helpful when you have a vague research idea but do not yet know how to turn it into a project.

For example, you might begin with:

> I am interested in whether planets can survive in binary star systems. Help me turn this broad idea into several possible undergraduate research questions. For each one, suggest the required background, possible methods, data or simulations needed, and a realistic first step.

The AI might help you organize the idea into categories such as:

- a literature review question,
- a numerical simulation project,
- an observational data project,
- a comparison between analytic theory and simulations,
- a visualization or teaching-focused project.

From there, you can ask for a more concrete plan:

> Turn this idea into a four-week research plan. Include weekly goals, skills to learn, code or data needed, expected outputs, and possible problems.

This kind of prompt can help you move from curiosity to action. The plan will still need to be checked and revised, but it gives you a starting structure.

## AI and your research log

Your research log is one of the best places to use AI productively. You can paste your notes into an AI tool and ask it to help you organize them.

Useful prompts include:

> Summarize today's research log into goals, actions taken, results, problems, and next steps.

> Identify the unresolved questions in this research log.

> Turn these notes into a short update I can discuss with my research advisor.

> Based on this log, what should I try first in my next research session?

This works best when your research log is specific. Record what you tried, what changed, what failed, and what you think it means.

## Appropriate use

Using AI tools is appropriate when they help you learn, organize, test, or communicate your own work. It is not appropriate to present AI-generated text, code, or analysis as if it were work you fully understand and verified.

Before using AI-generated material in a report, presentation, notebook, or manuscript, make sure you can explain it yourself.

A useful standard is:

> If I cannot explain it, I should not present it as my result.

AI tools can make research more accessible, but the responsibility for understanding and verifying the work remains with the researcher.

## Suggested videos and demonstrations

Videos can be useful for seeing how AI tools work in practice. However, they should be treated as demonstrations rather than complete instructions. The best way to learn these tools is to watch briefly, then try the workflow yourself using a real paper, textbook chapter, or research log.

### Prompt engineering basics

The first skill to practice is writing clear prompts. A good prompt gives the AI tool context, a task, constraints, and an expected format.

```{youtube} jNNatjruXx8
:width: 560
:height: 315
:align: center
```

After watching, try writing a prompt that includes:

- what you are working on,
- what background level the response should assume,
- what task you want completed,
- what format you want the answer in.

### NotebookLM for source-based research

NotebookLM is useful when you want AI help grounded in specific sources that you provide, such as papers, notes, PDFs, textbook sections, or research logs.

```{youtube} EOmgC3-hznM
:width: 560
:height: 315
:align: center
```

After watching, practice with one paper or one chapter. Upload the source, ask for the main research question, ask for the assumptions, then ask for a list of sections you should read carefully.

### Illuminate for first-pass paper summaries

Illuminate can help turn complex papers into AI-generated audio summaries. This can be useful before a careful reading, especially when you are trying to understand the big picture of a dense paper.

```{youtube} 59bU5zrgPkc
:width: 560
:height: 315
:align: center
```

After listening to an AI-generated summary, return to the original paper. Check the abstract, figures, methods, and conclusions yourself. Audio summaries can help you get oriented, but they should not replace reading the paper.

### Practice after watching

Choose one research paper and try this workflow:

1. Search for the paper in NASA ADS.
2. Open the arXiv or published version.
3. Upload the paper to NotebookLM.
4. Ask NotebookLM for the research question, methods, assumptions, and main result.
5. Use Illuminate or a similar audio-summary tool for a first-pass overview.
6. Return to the original paper and verify the summary.
7. Write your own short explanation in your research log.

The goal is not to let AI read the paper for you. The goal is to use AI to lower the barrier to your own careful reading.