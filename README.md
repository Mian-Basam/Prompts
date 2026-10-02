# Prompts

A collection of LLM prompts I use for technical content work: writing and reviewing persona-driven developer blogs, and running AI tutors for interactive courses.

## BlogPrompt/

| File | Purpose |
|------|---------|
| `Blog Wrting Prompt.txt` | Co-author prompt for a beginner-friendly, persona-driven blog (React beginner persona) |
| `Blog Making Guidelines 2.txt` | Co-author prompt for an experienced-backend persona with a pragmatic, story-driven tone |
| `Blog Guideline.txt` | Editor prompt that critically reviews a draft against editorial and persona guidelines |
| `Course prompt.txt` | Socratic React tutor that nudges learners toward answers with hints instead of giving solutions |
| `Couse2.txt` | A shorter variant of the React tutor prompt |

## How to use

Paste a prompt into your LLM of choice, fill in the placeholders (topic, persona, draft), and iterate. The tutor prompts use XML-style sections (`<about-you>`, `<style>`) so they slot into a system prompt.
