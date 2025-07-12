# Architecture Overview

## Core Modules
1. Vulnerability Prediction Engine (ML + code features, API hosted)
2. Patch Suggestion Engine (AI and heuristics)
3. Patch Simulator (Docker-based environment)
4. AI Red Team Agent (simulate exploits, API controlled)
5. Dashboard + CI/CD Integration

## Flow
Source Code → Scan + Predict → Patch → Simulate → Validate → Report