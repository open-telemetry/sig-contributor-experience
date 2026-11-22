# Using Generative AI Responsibly in OpenTelemetry Contributions

**Target length:** 5–6 minutes
**Audience:** OpenTelemetry contributors who use, or are considering using, generative AI tools.

---

## 1. Introduction — Using AI to Support Your Contribution (~30 sec)

**On screen:** Open the OpenTelemetry Community repository: https://github.com/open-telemetry/community

**Narration:**

Welcome back to the How to Contribute to OpenTelemetry series.

I’m Abhimanyu Narwal, a contributor and member of the OpenTelemetry Contributor Experience SIG.

In the previous video, we looked at preparing and submitting a contribution.

Now we’ll focus on using generative AI during that process.

AI can help you explore unfamiliar code, draft changes, and find potential problems. We’ll look at how to use that help while taking responsibility for your work and respecting maintainers’ time.

---

## 2. Maintainer Attention and Contributor Trust (~35 sec)

**On screen:** Show (using graphics):

`Focused Changes → Clear Communication → Response to Feedback → Trust`

**Narration:**

Maintainers have limited time to review issues, pull requests, and discussions.

A change that takes seconds to generate may still take hours to review, especially if it is large, unclear, or unverified.

Trust grows when contributors submit work they understand, explain their decisions, and respond to feedback.

An AI tool can support your work, but you still need to be available to answer questions and collaborate with reviewers.

That continued participation matters as much as the initial submission.

---

## 3. Patterns That Make Contributions Harder to Review (~50 sec)

**On screen:** Show each pattern alongside a better approach (use graphics to illustrate the comparison):

| Pattern | Better approach |
| --- | --- |
| Submitting without understanding the output | Review and understand every change |
| Oversized pull requests | Keep each contribution focused |
| Long generated descriptions and comments | Explain the change in your own words |
| Submitting and disappearing | Respond to questions and feedback |

**Narration:**

There are a few patterns to avoid.

First, submitting generated work without understanding it. You should be able to explain what changed and why it addresses the problem.

Second, oversized pull requests. Keep each contribution focused on one outcome, and discuss broader work with maintainers before expanding the scope.

Third, lengthy generated communication. A useful description explains the problem, the change, and how you verified it. Keep comments relevant, and communicate in your own words. Your English does not need to be perfect.

Finally, submitting and disappearing. Stay involved after opening the pull request. Answer questions, address feedback, and tell reviewers if you need help or time away.

---

## 4. Good Ways to Use AI (~50 sec)

**On screen:** Show three uses (use graphics to illustrate each use):

- **Explore:** Repository structure, contribution instructions, unfamiliar code, and test commands.
- **Draft:** Focused changes to code, tests, or documentation.
- **Review locally:** Possible bugs, missing tests, and unclear explanations.

**Narration:**

AI can be useful at several points in a contribution.

When exploring a repository, ask it to explain an unfamiliar function or help locate the relevant tests. Check its explanation against the actual code and documentation, since generated answers can be outdated or incorrect.

When drafting a change, use a specific task. For example, ask for help writing a regression test for a bug you have reproduced. Review the test and confirm that it catches the problem.

Before submitting, you can also ask AI to inspect your local diff for possible mistakes.

Evaluate each suggestion yourself, and run the checks required by the repository.

---

## 5. OpenTelemetry’s Generative AI Contribution Policy (~45 sec)

**On screen:**

1. Open the [Generative AI Contribution Policy](https://github.com/open-telemetry/community/blob/main/policies/genai.md).
2. Show **The Short Version** and **Human Responsibility and Control**.
3. Highlight maintainer discretion, human responsibility, and disclosure.
4. Show the recommended `Assisted-by:` commit trailer and its model examples.

**Narration:**

OpenTelemetry’s Generative AI Contribution Policy applies across its projects.

It allows AI assistance, while giving maintainers discretion to hide or close contributions made partly or entirely with generative AI.

The human contributor must remain in control and review, understand, and validate the final output.

Do not rely on AI output as the sole basis for a contribution, including reviews or messages in issues and Slack.

If generative AI created most of your contribution, disclose that openly. For code, the recommended method is an Assisted-by commit trailer identifying the model used.

Disclosure does not replace review or validation.

---

## 6. Check Repository-Specific Requirements (~55 sec)

**On screen:**

1. Open the Collector Contrib [CONTRIBUTING.md](https://github.com/open-telemetry/opentelemetry-collector-contrib/blob/main/CONTRIBUTING.md).
2. Find **AI-assisted contributions**.
3. Open the linked [AGENTS.md](https://github.com/open-telemetry/opentelemetry-collector-contrib/blob/main/AGENTS.md).
4. Highlight the rules for descriptions, comments, tests, and commit trailers.
5. Open the repository’s pull request template and show the human authorship checkbox without selecting it.

**Narration:**

Individual repositories may add more specific requirements. Read their CONTRIBUTING file and any linked instructions, including AGENTS.md.

Collector Contrib is one example.

Its guidance requires the human contributor to write the pull request description and issue or pull request comments.

An AI agent must ask for the content of each description section and use your answers verbatim. You must also check the human authorship box yourself before the pull request is ready for review.

The instructions cover tests and disclosure through an Assisted-by trailer. They also say to avoid Co-authored-by trailers for AI assistance, which can cause CLA checks to fail.

Check the current instructions in the repository where you plan to contribute.

---

## 7. A Responsible AI-Assisted Workflow (~40 sec)

**On screen:** Display the contribution path (use graphics to illustrate each step):

```text
Understand the Issue and Contribution Guidelines
       ↓
Use AI to Explore or Draft a Focused Change
       ↓
Review, Test, and Verify Locally
       ↓
Explain Your Work and Disclose AI Assistance
       ↓
Respond to Review Feedback
```

**Narration:**

Here’s how those steps fit together.

Start by understanding the issue and reading the project and repository guidance.

Use AI to help explore the code or draft a focused change.

Inspect the diff, verify its behavior, and run the required tests. Be clear about what you checked and any limitations.

Write a concise explanation that reflects your understanding, follow the repository’s communication rules, and disclose AI assistance as directed.

Then stay engaged through review. If you cannot explain part of the change, investigate it before asking someone else to review it.

---

## 8. Wrap-Up (~20 sec)

**On screen:** (Use the above generated graphic):

`Understand Your Change → Verify Your Work → Communicate Clearly → Stay Involved`

**Narration:**

AI can help you learn a repository, prepare a focused contribution, and find problems before submission.

You remain responsible for the result and for working with the community through review.

Read the applicable guidance, verify your work, and keep your own understanding visible in the contribution.

We look forward to seeing your contributions.
