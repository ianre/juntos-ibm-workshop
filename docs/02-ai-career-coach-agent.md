# Step 2: Create the AI Career Coach Agent

This is your second specialist agent. It answers questions about AI's impact on careers, education pathways, workforce skills, and career planning.

## You will use

- [knowledge-base/pdf/ai-career-coach-guide.pdf](../knowledge-base/pdf/ai-career-coach-guide.pdf)
- [knowledge-base/pdf/ai-career-coach-faq.pdf](../knowledge-base/pdf/ai-career-coach-faq.pdf)
- `AI Career Coach Agent` content from [copy-paste/agent-config.md](../copy-paste/agent-config.md)

## Create the agent

1. Open the main menu in watsonx Orchestrate.
2. Click `Create new agent`. (Or open `Build` in the hamburger menu and select `Create Agent`)
3. Select `Create from Scratch`
4. Fill in:
   - Name: `AI Career Coach Agent`
   - Description: copy the `AI Career Coach Agent description` block from [copy-paste/agent-config.md](../copy-paste/agent-config.md)
5. Click `Create`.

## Upload knowledge

1. Go to `Knowledge`.
2. Click `Add knowledge` -> `New Knowledge` -> `Upload files` -> `Next`.
3. Upload:
   - [knowledge-base/pdf/ai-career-coach-guide.pdf](../knowledge-base/pdf/ai-career-coach-guide.pdf)
   - [knowledge-base/pdf/ai-career-coach-faq.pdf](../knowledge-base/pdf/ai-career-coach-faq.pdf)
4. Paste the `AI Career Coach knowledge description` from [copy-paste/agent-config.md](../copy-paste/agent-config.md).
5. Name it something like `Career Coach Knowledge`.
6. Save.

## Configure behavior

Paste the `AI Career Coach Agent behavior` block from [copy-paste/agent-config.md](../copy-paste/agent-config.md) into the `Behavior` section.

## Quick test

Use one of the prompts from [copy-paste/test-prompts.md](../copy-paste/test-prompts.md), such as:

> How is AI changing jobs in healthcare, and what skills should I develop if I want to work in that field?

Check for three things:

1. The answer discusses AI's impact on careers and relevant skills
2. The answer cites the knowledge files
3. The answer includes both human and technical skills when relevant

## Deploy

1. Click `Deploy`
2. Confirm with `Deploy`

## Checkpoint

You are done with Step 2 when:

- The agent exists
- The two AI career coach PDFs are attached
- The quick test works
- The agent is deployed

## Next step

Go to [docs/03-supervisor-agent.md](03-supervisor-agent.md).
