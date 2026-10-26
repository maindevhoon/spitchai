# SpitchAI

**Describe the work. Generate its backend. Talk to the agent. Test it. Ship it.**

SpitchAI is a no-code voice agent builder designed for the Build Arena ElevenLabs track. A user describes a task in plain language. The platform determines the inputs, computation and integrations that task requires, assembles an execution pipeline, and connects it to an ElevenLabs voice agent.

## Core approach

The proposed compiler turns a task specification into a typed tool graph and versioned runtime manifest. Supported modules and task expressions provide the initial computational capabilities. The voice agent calls these tools during a conversation and explains their structured results.

The architecture supports different kinds of work rather than one industry. Signal analysis, custom calculations and workflow coordination illustrate the kinds of capabilities a task may require.

## Hackathon build

- Generate an editable agent configuration and execution plan from a request.
- Compose supported modules, validate their inputs and outputs, and expose callable tools.
- Test live with ElevenLabs, including conversation transcripts and tool results.
- Refine through chat or forms and rebuild affected logic.
- Publish a web experience and review session traces. Include a phone integration demonstration or the simulation permitted by the track.

The initial scope uses a bounded module catalog. Broader capability coverage and isolated module generation form the expansion path.

## Demonstration plan

1. Enter a fresh request within the supported capabilities.
2. Inspect the generated input and execution plan.
3. Compare actual tool outputs with known answers.
4. Talk to the ElevenLabs agent and publish the experience.
5. Change a computational requirement and demonstrate the changed backend without manual application-specific edits.

## Proposed stack

React for the builder and browser input capture, Node.js for compilation and execution, PostgreSQL for configuration and sessions, and ElevenLabs for the voice agent layer.

See [architecture](docs/architecture.md) and the [submission deck](submission/SpitchAI-Build-Arena-Submission.pptx).

## Team

**builders.io**  
Jaypee Institute of Information Technology  
Aanya Mahajan & Devbrat Nayak

