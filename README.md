# Linkedin-agent-gpt
LinkedIn Agent for ChatGPT

A ChatGPT adaptation of "avi691/linkedin-agent-skill" (https://github.com/avi691/linkedin-agent-skill).

Objective

Preserve the original project's 11 specialized LinkedIn workflows, scoring rubrics, hook formulas, writing-cleanup rules, and quality checks while adapting its execution model for ChatGPT.

Supported Workflows

- "LI-POST" — Create LinkedIn posts
- "LI-COMMENT" — Draft comments on other people's posts
- "LI-REPLY" — Classify and draft replies to comments
- "LI-PROFILE" — Score and optimize a LinkedIn profile
- "LI-PLAN" — Build a weekly content and engagement plan
- "LI-HUMAN" — Clean text and assess writing quality
- "LI-CAROUSEL" — Create document/carousel content
- "LI-REPURPOSE" — Turn source material into distinct posts
- "LI-DM" — Draft connection notes and follow-up messages
- "LI-INBOX" — Classify supplied messages and draft replies
- "LI-AUDIT" — Analyze post-performance metrics

Porting Requirements

1. Use the upstream repository as the canonical source.
2. Preserve original workflow definitions and source assets wherever possible.
3. Preserve the original hook formulas, profile-scoring rubric, cleanup lexicon, and Python behavior.
4. Replace Claude-specific plugin integration with ChatGPT-compatible instructions and workflows.
5. Document any behavior that cannot be reproduced natively in ChatGPT.
6. Do not introduce a Google Colab dependency.
7. Do not invent personal experiences, achievements, credentials, metrics, or evidence.
8. Never publish posts, send messages, or automate LinkedIn activity without an explicitly authorized integration and user approval.
9. Include tests or validation checks for any ported scripts and report only tests that were actually run.

Repository Status

This repository is the destination for the ChatGPT adaptation. The README is an initial project description, not evidence that the port is complete.

License

Follow the license of the upstream project and preserve its required attribution and notices.
