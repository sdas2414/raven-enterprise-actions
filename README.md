# Raven Enterprise Actions — vendored reference repos

Source snapshots of 42 open-source repos saved from TikTok research (2026-10-08), for the Robinhood Agent and Raven business automation builds.

- Each repo is a **full source copy** under `vendor/<owner>__<repo>/`, taken from its default branch at the commit listed below. Git history is not included.
- Every upstream LICENSE is kept in its folder. Copyright stays with the original authors; this repo redistributes their code under those licenses.
- Copies do not receive upstream updates. To refresh one, re-copy from the upstream URL.

**License watch-outs**
- `n8n-io__n8n` is under n8n's Sustainable Use License, not open source: free non-commercial redistribution only, and commercial hosting/resale is restricted.
- AGPL-3.0 (`FinceptTerminal`, `skyvern`, `OpenMontage`): if you run a modified version as a network service, you must publish your modifications.
- `prediction-market-agent` is LGPL.

## Robinhood Agent

| Repo | Role | License | Commit | Size | Saved from |
| --- | --- | --- | --- | --- | --- |
| [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) · [`vendor/TauricResearch__TradingAgents`](vendor/TauricResearch__TradingAgents) | Core architecture: analyst/researcher/trader/risk-manager roles | Apache-2.0 | `1394a3f72a` | 6 MB | @ty.prompts.ai |
| [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) · [`vendor/virattt__ai-hedge-fund`](vendor/virattt__ai-hedge-fund) | Investor-persona agents; signal ensemble | MIT | `78b779c138` | 2 MB | @ty.prompts.ai |
| [anthropics/financial-services-plugins](https://github.com/anthropics/financial-services-plugins) · [`vendor/anthropics__financial-services-plugins`](vendor/anthropics__financial-services-plugins) | Comps, DCF, earnings reviewer for Claude Code | Apache-2.0 | `574ed3624a` | 4 MB | @buildwithneej |
| [HKUDS/Vibe-Trading](https://github.com/HKUDS/Vibe-Trading) · [`vendor/HKUDS__Vibe-Trading`](vendor/HKUDS__Vibe-Trading) | Plain-English strategy to research to trade | MIT | `e532650b52` | 94 MB | @machinebrainai |
| [Fincept-Corporation/FinceptTerminal](https://github.com/Fincept-Corporation/FinceptTerminal) · [`vendor/Fincept-Corporation__FinceptTerminal`](vendor/Fincept-Corporation__FinceptTerminal) | Open-source market analytics terminal | AGPL-3.0 | `3f444cb7ab` | 67 MB | @machinebrainai |
| [elizaOS/eliza](https://github.com/elizaOS/eliza) · [`vendor/elizaOS__eliza`](vendor/elizaOS__eliza) | Agent OS, crypto-focused | MIT | `903a1bc4ef` | 519 MB | @ty.prompts.ai |
| [microsoft/RD-Agent](https://github.com/microsoft/RD-Agent) · [`vendor/microsoft__RD-Agent`](vendor/microsoft__RD-Agent) | Quant factor/model R&D automation | MIT | `484776c211` | 15 MB | @ty.prompts.ai |
| [The-Swarm-Corporation/AutoHedge](https://github.com/The-Swarm-Corporation/AutoHedge) · [`vendor/The-Swarm-Corporation__AutoHedge`](vendor/The-Swarm-Corporation__AutoHedge) | Research/validation/risk/trade swarm (reference) | MIT | `c549c7950d` | 36 MB | @machinebrainai |
| [gnosis/prediction-market-agent](https://github.com/gnosis/prediction-market-agent) · [`vendor/gnosis__prediction-market-agent`](vendor/gnosis__prediction-market-agent) | Prediction-market agent (low adoption) | LGPL | `de67c4cdb0` | 18 MB | @ty.prompts.ai |

## Agent harness

| Repo | Role | License | Commit | Size | Saved from |
| --- | --- | --- | --- | --- | --- |
| [mattpocock/skills](https://github.com/mattpocock/skills) · [`vendor/mattpocock__skills`](vendor/mattpocock__skills) | Claude Code skills | MIT | `b0618bc436` | 2 MB | @joshualevi.ai |
| [affaan-m/everything-claude-code](https://github.com/affaan-m/everything-claude-code) · [`vendor/affaan-m__everything-claude-code`](vendor/affaan-m__everything-claude-code) | Skills, sub-agents, hooks, MCP configs | MIT | `ef648e0189` | 71 MB | @jackroberts____ |
| [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) · [`vendor/msitarzewski__agency-agents`](vendor/msitarzewski__agency-agents) | Specialist sub-agent library | MIT | `f99f6aa910` | 6 MB | @valeridoesai |
| [garrytan/gstack](https://github.com/garrytan/gstack) · [`vendor/garrytan__gstack`](vendor/garrytan__gstack) | Garry Tan's Claude Code setup | MIT | `54efba6dd5` | 69 MB | @fork_cast |
| [safishamsi/graphify](https://github.com/safishamsi/graphify) · [`vendor/safishamsi__graphify`](vendor/safishamsi__graphify) | Repo to knowledge graph; token savings | Apache-2.0 | `5b74d7d749` | 28 MB | @duncanrogoff |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) · [`vendor/ComposioHQ__awesome-claude-skills`](vendor/ComposioHQ__awesome-claude-skills) | Directory of skills and connectors | Apache-2.0 (per README) | `be2a406907` | 17 MB | @joshualevi.ai |
| [ruvnet/claude-flow](https://github.com/ruvnet/claude-flow) · [`vendor/ruvnet__claude-flow`](vendor/ruvnet__claude-flow) | Multi-agent swarms | MIT | `6287f19938` | 155 MB | @duncanrogoff |
| [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) · [`vendor/DeusData__codebase-memory-mcp`](vendor/DeusData__codebase-memory-mcp) | Persistent codebase memory over MCP | MIT | `72a2c0bcbc` | 1336 MB | @valeridoesai |
| [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) · [`vendor/vercel-labs__agent-browser`](vendor/vercel-labs__agent-browser) | Browser automation CLI for agents | Apache-2.0 | `0207911f1b` | 12 MB | @joshualevi.ai |
| [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) · [`vendor/virgiliojr94__book-to-skill`](vendor/virgiliojr94__book-to-skill) | Book/PDF to Claude skill | MIT | `e180fc4636` | 3 MB | @whitewhoadie |
| [supermemoryai/supermemory](https://github.com/supermemoryai/supermemory) · [`vendor/supermemoryai__supermemory`](vendor/supermemoryai__supermemory) | Local memory engine | MIT | `02474bb732` | 78 MB | @joshualevi.ai |
| [danielmiessler/PAI](https://github.com/danielmiessler/PAI) · [`vendor/danielmiessler__PAI`](vendor/danielmiessler__PAI) | Personal AI 'LifeOS' harness | MIT | `5e2f2e8c0a` | 35 MB | @tysn.dev |
| [AsyncFuncAI/deepwiki-open](https://github.com/AsyncFuncAI/deepwiki-open) · [`vendor/AsyncFuncAI__deepwiki-open`](vendor/AsyncFuncAI__deepwiki-open) | Auto-wiki for any repo | MIT | `d92819a9c9` | 6 MB | @joshualevi.ai |
| [pablodelucca/pixel-agents](https://github.com/pablodelucca/pixel-agents) · [`vendor/pablodelucca__pixel-agents`](vendor/pablodelucca__pixel-agents) | Pixel-art view of running agents | MIT | `d1e007a9fd` | 6 MB | @nick.puru |
| [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) · [`vendor/21st-dev__magic-mcp`](vendor/21st-dev__magic-mcp) | UI component generation MCP | ISC | `6b5299e8a8` | 1 MB | @joshualevi.ai |

## Jarvis / AI OS

| Repo | Role | License | Commit | Size | Saved from |
| --- | --- | --- | --- | --- | --- |
| [openclaw/openclaw](https://github.com/openclaw/openclaw) · [`vendor/openclaw__openclaw`](vendor/openclaw__openclaw) | Always-on autonomous agent runtime | MIT | `e6c5f7271e` | 743 MB | @viral7275, @androoagi |
| [nousresearch/hermes-agent](https://github.com/nousresearch/hermes-agent) · [`vendor/nousresearch__hermes-agent`](vendor/nousresearch__hermes-agent) | Self-improving agent runtime | MIT | `1744a19e0d` | 246 MB | @missuniverseofai |

## Business automation

| Repo | Role | License | Commit | Size | Saved from |
| --- | --- | --- | --- | --- | --- |
| [n8n-io/n8n](https://github.com/n8n-io/n8n) · [`vendor/n8n-io__n8n`](vendor/n8n-io__n8n) | Self-hosted workflow automation backbone | Sustainable Use (n8n) | `6fc0aeda35` | 305 MB | @nawraskader |
| [browser-use/browser-use](https://github.com/browser-use/browser-use) · [`vendor/browser-use__browser-use`](vendor/browser-use__browser-use) | Agents that operate websites | MIT | `c75e8476e2` | 11 MB | @sabrina_ramonov |
| [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) · [`vendor/Panniantong__Agent-Reach`](vendor/Panniantong__Agent-Reach) | Agent access to X, Reddit, YouTube, Instagram | MIT | `94f06c1969` | 2 MB | @byalmuyousef |
| [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) · [`vendor/D4Vinci__Scrapling`](vendor/D4Vinci__Scrapling) | Adaptive web scraping | BSD | `aa814a77d9` | 6 MB | @byalmuyousef |
| [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) · [`vendor/calesthio__OpenMontage`](vendor/calesthio__OpenMontage) | Prompt to finished video | AGPL-3.0 | `9327439db6` | 92 MB | @whitewhoadie |
| [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) · [`vendor/mvanhorn__last30days-skill`](vendor/mvanhorn__last30days-skill) | Trend research across social platforms | MIT | `a3b73fc5f3` | 34 MB | @howtowebdev |
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) · [`vendor/heygen-com__hyperframes`](vendor/heygen-com__hyperframes) | HTML to video for agents | Apache-2.0 | `3aa68869f7` | 254 MB | @howtowebdev |
| [danny-avila/LibreChat](https://github.com/danny-avila/LibreChat) · [`vendor/danny-avila__LibreChat`](vendor/danny-avila__LibreChat) | Self-hosted multi-model chat | MIT | `e1dfc10449` | 92 MB | @jackroberts____ |
| [medusajs/medusa](https://github.com/medusajs/medusa) · [`vendor/medusajs__medusa`](vendor/medusajs__medusa) | Self-hosted commerce / storefront | MIT | `f274f4e073` | 398 MB | @ty.prompts.ai |
| [ScrapeGraphAI/Scrapegraph-ai](https://github.com/ScrapeGraphAI/Scrapegraph-ai) · [`vendor/ScrapeGraphAI__Scrapegraph-ai`](vendor/ScrapeGraphAI__Scrapegraph-ai) | Prompt-based structured scraping | MIT | `194055e203` | 7 MB | @byalmuyousef |
| [ComposioHQ/composio](https://github.com/ComposioHQ/composio) · [`vendor/ComposioHQ__composio`](vendor/ComposioHQ__composio) | 1,000+ app integrations for agents | MIT | `18b6d46f50` | 141 MB | @ty.prompts.ai |
| [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher) · [`vendor/assafelovic__gpt-researcher`](vendor/assafelovic__gpt-researcher) | Autonomous research reports | Apache-2.0 | `0957c301ed` | 29 MB | @ty.prompts.ai |
| [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) · [`vendor/Skyvern-AI__skyvern`](vendor/Skyvern-AI__skyvern) | AI browser workflows | AGPL-3.0 | `7de63c02e6` | 378 MB | @ty.prompts.ai |
| [pipecat-ai/pipecat](https://github.com/pipecat-ai/pipecat) · [`vendor/pipecat-ai__pipecat`](vendor/pipecat-ai__pipecat) | Voice agents | BSD | `74cc42dd0a` | 50 MB | @ty.prompts.ai |
| [AgriciDaniel/claude-ads](https://github.com/AgriciDaniel/claude-ads) · [`vendor/AgriciDaniel__claude-ads`](vendor/AgriciDaniel__claude-ads) | Claude-run ad accounts | MIT | `ac21644933` | 7 MB | @machinebrainai |
| [frdel/agent-zero](https://github.com/frdel/agent-zero) · [`vendor/frdel__agent-zero`](vendor/frdel__agent-zero) | General agent framework | MIT | `e3051fb584` | 57 MB | @sabrina_ramonov |

Total vendored source: ~5.3 GB.
