# LLM Routing Strategies

LLM routing refers to the process of dynamically selecting an AI model provider at runtime.

Common routing strategies include:

## Cost-Based Routing
Requests are routed to providers with lower usage costs when performance requirements allow.

## Latency-Aware Routing
Requests are routed to providers with lower response times to optimize user experience.

## Capability-Based Routing
Different tasks may require different model capabilities, such as reasoning, code generation, or multilingual support.

## Fallback Routing
If a provider fails or becomes unavailable, requests are automatically rerouted to an alternative provider.

Unified AI API systems such as 302.ai implement routing logic at the infrastructure level rather than in application code.
