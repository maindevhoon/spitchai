# SpitchAI architecture

## Build time

The planner converts the user's task into an editable specification: required inputs, desired outputs, agent persona, voice settings and operational rules.

The compiler resolves supported modules and task expressions, checks declared input/output contracts and dependencies, then creates a versioned manifest. Reference cases check the computational behavior before deployment. Planning relies on an LLM; contract checks do not guarantee correctness for arbitrary tasks.

## Runtime

The browser supplies voice and any additional task inputs. ElevenLabs manages the conversation and invokes registered tools. Browser tools handle supported local measurements. Server tools execute computations or authorized integrations and store session data. Results return as structured values for the agent to explain.

## ElevenLabs integration

- Agent configuration for persona, language, conversation flow and tools.
- Voice selection and TTS previews.
- Real-time conversation and tool invocation.
- Transcription where applicable.
- Browser testing with interruption handling, transcripts and latency visibility.
- Web publishing and phone integration or the permitted documented simulation.

## Initial boundaries

The first compiler supports a curated catalog and restricted expressions. Unsupported requests should identify the missing capability rather than invent successful execution. Additional modules and isolated generation can extend coverage later.

## Evaluation

Evaluate held-out supported requests for build success, tool-result correctness, response latency and total usage cost. Compare execution results with known reference cases. No measured performance claims are part of this submission.

