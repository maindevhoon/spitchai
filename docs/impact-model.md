# Illustrative impact model

The submission uses a hypothetical cost scenario to explain how reusable deterministic execution could affect usage costs. It is not a measured benchmark or provider pricing quote.

| Component | Baseline cost index | Compiled cost index |
| --- | ---: | ---: |
| Fixed voice, transport and other costs | 70 | 70 |
| Repeated LLM reasoning | 30 | 12 |
| Incremental deterministic execution | 0 | 3 |
| Total | 100 | 85 |

Assume that supported computations replace 60% of the baseline LLM reasoning spend. The remaining spend is `30 × 0.4 = 12`. Add 3 units for execution, giving `70 + 12 + 3 = 85`. Relative savings are `(100 − 85) / 100 = 15%`.

These assumed shares are illustrative. Real results depend on the task mix, model, token use, voice duration, infrastructure and tool costs. Savings could be smaller or negative. The comparison must use equivalent requirements and include all costs.

## Capability scope

Four planned capability types illustrate the scope of a configured agent:

1. Interpret the request and context.
2. Calculate using supported deterministic operations.
3. Validate against configured rules.
4. Act through authorized integrations.

The count is a product scope illustration. It is not an intelligence score, a measured multiplier, or a claim that competing agents cannot use these capabilities.

Tested rules can support repeatability for supported inputs. Planning and conversation remain probabilistic, and integrations can fail. Greater trust and adoption remain hypotheses for user testing.
