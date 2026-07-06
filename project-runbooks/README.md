# Project Runbooks

Deep-dive writeups of personal projects — architecture, request flow, design
decisions, and the interview-ready explanation of *why* each piece exists.
Unlike the other guides in this repo (which cover tools used on the job),
these are self-built projects, so the runbook doubles as prep for "walk me
through something you built."

## Projects

### [LLM Cost & Observability Stack](llm-cost-observability.md)
FinOps-style cost/token/latency/error tracking for LLM API usage — LiteLLM
proxy + Prometheus + Grafana, applying the same cost-attribution pattern used
for cloud spend to LLM spend instead. Covers full request-flow architecture,
every metric and PromQL query used, the real bugs hit while building it, and
likely interview Q&A.

<!-- Add new project runbooks below as they're built -->
