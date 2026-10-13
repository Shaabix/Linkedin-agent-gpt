# LinkedIn Agent for ChatGPT

ChatGPT-native adaptation scaffold for [avi691/linkedin-agent-skill](https://github.com/avi691/linkedin-agent-skill).

**Important:** This is not yet a full source-parity port. The ChatGPT workflow specification is included, but the original hook JSON, profile rubric JSON, humanizer lexicon, Python scripts, and verbatim upstream workflow files must still be imported and validated.

## Workflows
- `LI-POST` — Create LinkedIn posts
- `LI-COMMENT` — Draft comments on other people's posts
- `LI-REPLY` — Classify and draft replies to comments
- `LI-PROFILE` — Score and optimize a LinkedIn profile
- `LI-PLAN` — Build a weekly content and engagement plan
- `LI-HUMAN` — Clean text and assess writing quality
- `LI-CAROUSEL` — Create document/carousel content
- `LI-REPURPOSE` — Turn source material into distinct posts
- `LI-DM` — Draft connection notes and follow-up messages
- `LI-INBOX` — Classify supplied messages and draft replies
- `LI-AUDIT` — Analyze post-performance metrics

No Google Colab dependency. No LinkedIn publishing, messaging, scraping, or engagement automation.
