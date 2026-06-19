# Step 3: Create the Supervisor Agent

This is the only agent the student should talk to directly. Its job is to route each question to the correct specialist.

## You will use

- Both deployed specialist agents from Steps 1 and 2
- `Supervisor Agent` content from [copy-paste/agent-config.md](../copy-paste/agent-config.md)

## Create the agent

1. In watsonx Orchestrate, open `Build` in the hamburger menu and select `Create Agent`.
2. Select `Create from Scratch`
3. Fill in:
   - Name: `Supervisor Agent`
   - Description: copy the `Supervisor description` block from [copy-paste/agent-config.md](../copy-paste/agent-config.md)
4. Click `Create`.

## Add the specialist agents

1. Open the `Toolset` section.
2. Under the `Agents` subsection, click `Add agent`.
3. Choose `Add from local instance`.
4. Select:
   - `Scholarship Agent`
   - `Campus Resources Agent`
5. Click `Add to agent`.

## Configure behavior

Paste the `Supervisor behavior` block from [copy-paste/agent-config.md](../copy-paste/agent-config.md) into the `Behavior` section.

## Deploy

1. Click `Deploy`
2. Confirm with `Deploy`

## Checkpoint

You are done with Step 3 when:

- The supervisor exists
- Both specialist agents are connected in the Toolset
- The supervisor is deployed

## Next step

Go to [docs/04-test-in-web-chat.md](04-test-in-web-chat.md).
