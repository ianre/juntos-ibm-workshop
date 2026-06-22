# Step 4: Test in Web Chat

This is the moment where you confirm the multi-agent system actually works.

## Open the chat

1. Open the main menu in watsonx Orchestrate.
2. Click `Chat`.
3. In the agent dropdown, choose `Supervisor Agent`.

## Run three tests

Use the prompts in [copy-paste/test-prompts.md](../copy-paste/test-prompts.md).

### Test 1: Scholarships in English

> What scholarships are available for first-generation Hispanic students?

### Test 2: AI Career Coach in Spanish

> Que habilidades humanas y tecnicas necesito para tener exito en un mundo laboral con inteligencia artificial?

### Test 3: Multi-agent routing

> I need to find scholarships for next semester and I also want to know what skills I should develop for an AI-influenced job market.

## What to look for

1. Scholarship questions should be answered from the scholarship documents
2. Career planning and AI workforce questions should be answered from the AI career coach documents
3. Multi-topic questions should be answered in one combined response
4. The bot should match the language of the student
5. Citations should still appear in the specialist responses

## Use reasoning if available

If your instance includes `Show Reasoning`, open it while testing. This helps you see how the supervisor decided which agent to use.

## Checkpoint

You are done with Step 4 when:

- The supervisor responds in chat
- The bot routes each test correctly
- The bilingual behavior works

## Next step

Go to [docs/05-troubleshooting.md](05-troubleshooting.md).
