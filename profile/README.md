# LoopGrid

**The evidence layer for AI agents.**

### When AI agents act, LoopGrid preserves verifiable evidence of what happened.

AI agents can make consequential decisions, trigger tools, modify records, and initiate business actions. Traditional logs often cannot establish the complete history of who authorized an action, which policy applied, or what evidence supports its reported outcome.

**LoopGrid is decision-evidence infrastructure for AI agents.**

It captures consequential decisions and their supporting history, including:

- Agent identity and delegated authority
- Model and decision context
- Policy evaluations and human reviews
- Proposed actions, tool results, and external execution evidence
- Observed outcomes
- SHA-256 commitments and Ed25519-signed, tamper-evident history

Evidence can be exported and independently verified without relying on the running LoopGrid service.

### Start here

| Resource | Link |
|---|---|
| Website | [loopgrid.io](https://loopgrid.io/) |
| Developer quickstart | [Documentation](https://loopgrid.io/docs/) |
| Framework integrations | [Integration directory](https://loopgrid.io/integrations/) |
| Interactive demonstration | [Evidence demo](https://loopgrid.io/demo/) |
| Core infrastructure | [LoopGrid Core](https://github.com/cybertechsoft/loopgrid) |
| Offline verification | [LoopGrid Verify](https://pypi.org/project/loopgrid-verify/) |

### Build with LoopGrid

Use the SDK or integrate through existing agent frameworks and automation tools.

**Python SDK**
```bash
pip install loopgrid
```

**TypeScript / JavaScript SDK**
```bash
npm install @cybertechsoft/loopgrid
```

**Native integrations**

LangChain · LangGraph · Mastra · Agno · OpenAI Agents · Google ADK · Strands · CrewAI · Dify · n8n · MCP and more.

Browse the [integration documentation](https://loopgrid.io/integrations/) for supported paths, installation requirements, and validation boundaries.

### What verification means

LoopGrid verification establishes integrity and provenance properties of the evidence that was captured. It does not independently establish the correctness of an AI decision, the truth of every source claim, or the success of an external business action without supporting evidence.

The current Core release is intended for developer evaluation and design-partner validation. Production deployment requires appropriate operational and security controls.

### Work with us

We are looking for engineering teams building AI agents that perform consequential business actions, especially workflows requiring accountability, policy review, and independently verifiable evidence.

**Website:** https://loopgrid.io/

**GitHub:** https://github.com/loopgridio
