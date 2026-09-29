# Presentation AI Prompt Builder

A browser-based tool that creates a structured master prompt for
developing presentation content with an AI assistant.

## Live Tool

Open the Presentation AI Prompt Builder:

ADD_YOUR_GITHUB_PAGES_URL_HERE

## What This Tool Does

The Presentation AI Prompt Builder helps users define:

- the purpose of a presentation;
- the intended audience;
- the required decision or outcome;
- audience priorities;
- presentation timing;
- technical depth;
- sensitive context;
- source-material handling; and
- the required presentation output.

The tool converts these answers into a compact master prompt.

The generated prompt can be pasted into an AI assistant such as
Microsoft Copilot, ChatGPT, Claude, Gemini, or another suitable tool.

## Intended Workflow

1. Complete the questions in the builder.
2. Generate and copy the master prompt.
3. Paste the prompt into your chosen AI assistant.
4. Provide the AI with your source material.
5. The source material may be:
   - a PDF or document;
   - selected text;
   - an existing report;
   - presentation notes; or
   - background context.
6. The AI reviews the source material.
7. The AI asks only essential follow-up questions.
8. The AI generates the requested presentation content.

The source document is not uploaded to or stored by this website.

## Presentation Methods

The generated prompt incorporates four presentation methods:

### BLUF

Bottom Line Up Front. The presentation begins with the conclusion,
recommendation, requested decision, or most important message.

### SCQA

Situation, Complication, Question, and Answer. This provides a concise
narrative explaining why the presentation is necessary and what must
be resolved.

### Minto Pyramid

The main answer is supported by logically grouped arguments, which are
then supported by facts and evidence from the source material.

### Golden Thread

The presentation is organised around one central question. Every main
slide should help answer that question.

## The 85/15 Approach

The builder handles the repeatable presentation structure.

The user provides the situation-specific context that an AI cannot
reliably infer, including:

- stakeholder sensitivities;
- leadership priorities;
- known objections;
- confidential areas;
- exclusions; and
- special presentation constraints.

The 85/15 approach is a design philosophy of this tool, not a claim
that every presentation must follow an exact mathematical ratio.

## Recommended Prompt Length

The builder is designed to generate a compact master prompt.

The target length is approximately 450 to 750 words before extensive
user-provided information is added.

This is intended to provide enough instruction to control the
presentation workflow without unnecessarily competing with a long
report or PDF for the AI assistant's available context.

## Features

- Guided, step-by-step interface
- Plain-language questions
- Audience and outcome definition
- Presentation-time planning
- Audience-priority selection
- Technical-depth control
- Sensitive-context and exclusion fields
- PDF, text, document, and notes handover options
- Accuracy and assumption controls
- Configurable presentation deliverables
- BLUF, SCQA, Minto Pyramid, and Golden Thread guidance
- Review screen before prompt generation
- Copy-to-clipboard function
- Downloadable text prompt
- Approximate word and token count
- Responsive design for desktop and mobile use
- No installation or account required

## Privacy and Data Handling

This tool runs locally in the user's browser.

The current version:

- does not upload form answers to a server;
- does not store source documents;
- does not require users to sign in;
- does not use a database; and
- does not send the generated prompt to an AI service automatically.

Users are responsible for reviewing the privacy, confidentiality, and
data-handling requirements of the AI service into which they paste the
generated prompt or upload source material.

Do not upload confidential, personal, commercially sensitive, or
restricted information unless you are authorised to provide it to the
selected AI service.

## How to Use Locally

1. Download `index.html`.
2. Open the file using a modern web browser.
3. Complete the guided questions.
4. Generate the master prompt.
5. Copy the prompt into your chosen AI assistant.

No installation, web server, package manager, or build step is required.

## Technology

The tool uses:

- HTML
- CSS
- Vanilla JavaScript

It has no external application dependencies.

## Limitations

- The tool generates an AI prompt, not a PowerPoint file.
- Output quality depends on the information supplied by the user.
- Output quality also depends on the capabilities of the selected AI.
- AI-generated content should be reviewed before use.
- The presentation frameworks are guidance, not mandatory rules.
- The approximate token count is an estimate and may differ between
  AI systems.
- The tool does not verify the accuracy of source documents.

## Contributing

Suggestions, bug reports, and improvements are welcome.

Please use GitHub Issues to:

- report a problem;
- suggest a new feature;
- recommend a wording improvement; or
- describe an unexpected generated prompt.

When reporting an issue, do not include confidential presentation
content or source documents.

## Maintainer

Created and maintained by Muhamad Amirsyafiq bin Amirmusidi.

## License

See the `LICENSE` file for usage, modification, and distribution terms.
