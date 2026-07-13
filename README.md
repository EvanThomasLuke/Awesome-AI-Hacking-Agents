# Awesome-AI-Hacking-Agents
List of AI Hacking Agents - WORK IN PROGRESS PLEASE CONTRIBUTE!! I know I'm missing many companies and several open source. I'm going to add benchmark results for the few that have results. 

THESE REPOS ARE FOR EDUCATIONAL AND AUTHORIZED SECURITY TESTING PURPOSES ONLY. 

Please submit any I'm missing. You can just submit an issue with repo link and I will add to tables with details. 

There are currently ~64 open source AI hacking agents listed. I need to re-sort and recategorize, some technically aren't agents. 

Will be posting a comparative feature analysis soon (memory types, tools, etc). 

Come chat about AI hacking agents in the AI Hacking Discord https://discord.gg/9AJnkNe6RE

# Todo 

* add last commit and stars with csv so people can sort. Also add all benchmark scores.
* Merge tencent repos 

# Devin Deepwiki / Google Code Wiki 
Each of the open source tools contains deep wiki and code wiki links. You can use the Devin deepwiki MCP when your developing with your AI IDE/Agents to query open source repos to help you see what features others agents have. 

The free, public DeepWiki MCP server (https://mcp.deepwiki.com/mcp), which exposes structured tools (like ask_question, read_wiki_structure, and read_wiki_contents) that agents can call directly.Integrate it into your workflow by adding the MCP endpoint to tools-compatible agents/IDEs (Cursor, Claude Code, Windsurf, Continue.dev, etc.) — usually just a one-line config addition with no auth needed for public repos. Once connected, instruct your agent to leverage DeepWiki MCP (often paired with GitHub CLI) for tasks like:

https://docs.devin.ai/work-with-devin/deepwiki-mcp

# Open Source (WIP)

These are sorted by release date. 

Each github repo also contains a link to Devin deep wiki and Google Code wiki which provides detailed documentation and a Gemini chat interface to ask questions about the repo. (I've requested all of the columns without a link and will update once google processes them). 

I'm still updating this list with benchmark scores and more comments. 


<!-- OPENSOURCE_TABLE_START (managed by awesome_table.py — do not hand-edit rows outside this block) -->
| #  | Name                     | URL                                                                                  | Source        | Created / Published | Notes                                                                                                                                        | CodeWiki (empty are pending) | DeepWiki (empty are pending)                                     |
| -- | ------------------------ | ------------------------------------------------------------------------------------ | ------------- | ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------------------------- |
| 1  | AutoPentest-DRL          | https://github.com/crond-jaist/AutoPentest-DRL                                       | GitHub        | 2021-03-30          | Deep RL for automated pentesting                                                                                                             | https://codewiki.google/github.com/crond-jaist/autopentest-drl   | https://deepwiki.com/crond-jaist/AutoPentest-DRL                 |
| 2  | Reaper (Ghost Security)  | https://github.com/ghostsecurity/reaper                                              | GitHub        | 2022-11-28          |                                                                                                                                              | https://codewiki.google/github.com/ghostsecurity/reaper          | https://deepwiki.com/ghostsecurity/reaper                        |
| 3  | PentestGPT               | https://github.com/GreyDGL/PentestGPT                                                | GitHub        | 2023-02-27          | USENIX Security 2024                                                                                                                         | https://codewiki.google/github.com/greydgl/pentestgpt             | https://deepwiki.com/GreyDGL/PentestGPT                          |
| 4  | hackingBuddyGPT          | https://github.com/ipa-lab/hackingBuddyGPT                                           | GitHub        | 2023-08-02          |                                                                                                                                              | https://codewiki.google/github.com/ipa-lab/hackingbuddygpt        | https://deepwiki.com/ipa-lab/hackingBuddyGPT                     |
| 5 | Nebula | https://github.com/berylliumsec/nebula | GitHub | 2023-09-30 |  | https://codewiki.google/github.com/berylliumsec/nebula | https://deepwiki.com/berylliumsec/nebula |
| 6  | nyuctf_agents (D-CIPHER) | https://github.com/NYU-LLM-CTF/nyuctf_agents                                         | GitHub        | 2024-03-13          | arXiv: 2502.10931 (Feb 15 2025)                                                                                                              | https://codewiki.google/github.com/nyu-llm-ctf/nyuctf_agents     | https://deepwiki.com/NYU-LLM-CTF/nyuctf_agents                   |
| 7 | Pentest-Swarm-AI | https://github.com/Armur-Ai/Pentest-Swarm-AI | GitHub | 2024-03-26 |  | https://codewiki.google/github.com/armur-ai/pentest-swarm-ai | https://deepwiki.com/Armur-Ai/Pentest-Swarm-AI |
| 8 | ReaperAI | https://github.com/tac01337/ReaperAI | GitHub | 2024-04-19 | arXiv: 2406.07561 (May 9 2024) | https://codewiki.google/github.com/tac01337/reaperai | https://deepwiki.com/tac01337/ReaperAI |
| 9  | BreachSeek (arXiv only)  | https://arxiv.org/abs/2409.03789                                                     | arXiv         | 2024-08-31          | No associated repo listed                                                                                                                    |                                                                   |                                                                  |
| 10 | vulnhuntr | https://github.com/protectai/vulnhuntr | GitHub | 2024-10-15 |  | https://codewiki.google/github.com/protectai/vulnhuntr | https://deepwiki.com/protectai/vulnhuntr |
| 11 | HackSynth | https://github.com/aielte-research/HackSynth | GitHub | 2024-11-27 |  | https://codewiki.google/github.com/aielte-research/hacksynth | https://deepwiki.com/aielte-research/HackSynth |
| 12 | PentAGI                  | https://github.com/vxcontrol/pentagi                                                 | GitHub        | 2025-01-06          |                                                                                                                                              | https://codewiki.google/github.com/vxcontrol/pentagi              | https://deepwiki.com/vxcontrol/pentagi                           |
| 13 | VulnBot                  | https://github.com/KHenryAegis/VulnBot                                               | GitHub        | 2025-01-20          |                                                                                                                                              | https://codewiki.google/github.com/khenryaegis/vulnbot            | https://deepwiki.com/KHenryAegis/VulnBot                         |
| 14 | BoxPwnr | https://github.com/0ca/BoxPwnr | GitHub | 2025-01-26 |  | https://codewiki.google/github.com/0ca/boxpwnr | https://deepwiki.com/0ca/BoxPwnr |
| 15 | Agentic Radar            | https://github.com/splx-ai/agentic-radar                                             | GitHub        | 2025-02-12          |                                                                                                                                              | https://codewiki.google/github.com/splx-ai/agentic-radar         | https://deepwiki.com/splx-ai/agentic-radar                       |
| 16 | D-CIPHER (paper) | https://arxiv.org/abs/2502.10931, repo: https://github.com/NYU-LLM-CTF/nyuctf_agentt | arXiv, github | 2025-02-15 | Repo: NYU-LLM-CTF/nyuctf_agents | https://codewiki.google/github.com/nyu-llm-ctf/nyuctf_agents | https://deepwiki.com/NYU-LLM-CTF/nyuctf_agents |
| 17 | Claude Code | https://github.com/anthropics/claude-code | GitHub | 2025-02-22 | Plugins README linked | https://codewiki.google/github.com/anthropics/claude-code | https://deepwiki.com/anthropics/claude-code |
| 18 | CAI (Cybersecurity AI) | https://github.com/aliasrobotics/cai | GitHub | 2025-03-31 |  | https://codewiki.google/github.com/aliasrobotics/cai | https://deepwiki.com/aliasrobotics/cai |
| 19 | agent-scan | https://github.com/snyk/agent-scan | GitHub | 2025-04-07 |  | https://codewiki.google/github.com/snyk/agent-scan | https://deepwiki.com/snyk/agent-scan |
| 20 | pentestagent             | https://github.com/GH05TCREW/pentestagent                                            | GitHub        | 2025-05-15          |                                                                                                                                              | https://codewiki.google/github.com/gh05tcrew/pentestagent        | https://deepwiki.com/GH05TCREW/pentestagent                      |
| 21 | Cyber-AutoAgent          | https://github.com/westonbrown/Cyber-AutoAgent (archived), active https://github.com/double16/cyber-autoagent-ng                                       | GitHub        | 2025-05-26          | 85% score on xbow top open source score                                                                                                      | https://codewiki.google/github.com/westonbrown/cyber-autoagent    | https://deepwiki.com/westonbrown/Cyber-AutoAgent                 |
| 22 | Decepticon | https://github.com/purpleailab/decepticon | GitHub | 2025-06-06 |  | https://codewiki.google/github.com/purpleailab/decepticon | https://deepwiki.com/purpleailab/decepticon |
| 23 | raink | https://github.com/BishopFox/raink | GitHub | 2025-06-12 | LLM document ranking used for vulnerability identification workflows. | https://codewiki.google/github.com/bishopfox/raink | https://deepwiki.com/BishopFox/raink |
| 24 | ghostcrew                | https://github.com/shakenetwork/ghostcrew                                            | GitHub        | 2025-06-13          |                                                                                                                                              | https://codewiki.google/github.com/shakenetwork/ghostcrew        | https://deepwiki.com/shakenetwork/ghostcrew                      |
| 25 | ARTEMIS                  | https://github.com/Stanford-Trinity/ARTEMIS                                          | GitHub        | 2025-07-07          |                                                                                                                                              | https://codewiki.google/github.com/stanford-trinity/artemis       | https://deepwiki.com/Stanford-Trinity/ARTEMIS                    |
| 26 | metis | https://github.com/arm/metis | GitHub | 2025-07-07 |  | https://codewiki.google/github.com/arm/metis | https://deepwiki.com/arm/metis |
| 27 | hexstrike-ai | https://github.com/0x4m4/hexstrike-ai | GitHub | 2025-07-10 |  | https://codewiki.google/github.com/0x4m4/hexstrike-ai | https://deepwiki.com/0x4m4/hexstrike-ai |
| 28 | fraim | https://github.com/fraim-dev/fraim | GitHub | 2025-07-10 | Framework for security teams to build AI-powered workflows that orchestrate agents, tools, and security outputs. | https://codewiki.google/github.com/fraim-dev/fraim | https://deepwiki.com/fraim-dev/fraim |
| 29 | RepoAudit | https://github.com/PurCL/RepoAudit | GitHub | 2025-07-10 | Autonomous LLM agent for repo-level code auditing with memory and on-demand codebase exploration. | https://codewiki.google/github.com/purcl/repoaudit | https://deepwiki.com/PurCL/RepoAudit |
| 30 | Repeater Strike | https://github.com/hackvertor/repeat-strike | GitHub | 2025-07-17 | AI-powered Burp extension for expanding manual Repeater findings such as IDORs across proxy history. | https://codewiki.google/github.com/hackvertor/repeat-strike | https://deepwiki.com/hackvertor/repeat-strike |
| 31 | deadend-cli | https://github.com/xoxruns/deadend-cli | GitHub | 2025-07-22 |  | https://codewiki.google/github.com/xoxruns/deadend-cli | https://deepwiki.com/xoxruns/deadend-cli |
| 32 | Strix                    | https://github.com/usestrix/strix                                                    | GitHub        | 2025-08-05          |                                                                                                                                              | https://codewiki.google/github.com/usestrix/strix                 | https://deepwiki.com/usestrix/strix                              |
| 33 | hackerai | https://github.com/hackerai-tech/hackerai | GitHub | 2025-08-09 |  | https://codewiki.google/github.com/hackerai-tech/hackerai | https://deepwiki.com/hackerai-tech/hackerai |
| 34 | NeuroSploit              | https://github.com/CyberSecurityUP/NeuroSploit                                       | GitHub        | 2025-08-17          |                                                                                                                                              | https://codewiki.google/github.com/cybersecurityup/neurosploit    | https://deepwiki.com/CyberSecurityUP/NeuroSploit                 |
| 35 | BruteForceAI | https://github.com/MorDavid/BruteForceai | GitHub | 2025-08-25 | LLM-powered brute-force tool combining AI reasoning with automated login attacks. | https://codewiki.google/github.com/mordavid/bruteforceai | https://deepwiki.com/MorDavid/BruteForceai |
| 36 | MAPTA                    | https://github.com/arthurgervais/mapta                                               | GitHub        | 2025-08-28          | arXiv: 2508.20816 (Aug 28 2025)                                                                                                              | https://codewiki.google/github.com/arthurgervais/mapta           | https://deepwiki.com/arthurgervais/mapta                         |
| 37 | Beelzebub | https://github.com/mariocandela/beelzebub | GitHub | 2025-08 | Offensive AI security toolkit and honeypot framework for malicious AI-agent behavior. | https://codewiki.google/github.com/mariocandela/beelzebub | https://deepwiki.com/mariocandela/beelzebub |
| 38 | Hound | https://github.com/scabench-org/hound | GitHub | 2025-08 | Open-source autonomous agents for code security auditing; builds and refines knowledge graphs for deep code reasoning. | https://codewiki.google/github.com/scabench-org/hound | https://deepwiki.com/scabench-org/hound |
| 39 | agentic-soc-platform     | https://github.com/FunnyWolf/agentic-soc-platform                                    | GitHub        | 2025-09-07          |                                                                                                                                              | https://codewiki.google/github.com/funnywolf/agentic-soc-platform | https://deepwiki.com/FunnyWolf/agentic-soc-platform              |
| 40 | seclab-taskflow-agent    | https://github.com/GitHubSecurityLab/seclab-taskflow-agent                           | GitHub        | 2025-09-08          | GitHub Security Lab                                                                                                                          | https://codewiki.google/github.com/githubsecuritylab/seclab-taskflow-agent| https://deepwiki.com/GitHubSecurityLab/seclab-taskflow-agent     |
| 41 | auto-exploits | https://github.com/Valmarelox/auto-exploits | GitHub | 2025-09-11 | Repository associated with generated exploit automation examples. | https://codewiki.google/github.com/valmarelox/auto-exploits | https://deepwiki.com/Valmarelox/auto-exploits |
| 42 | Shannon | https://github.com/KeygraphHQ/shannon | GitHub | 2025-09-27 | repo claims high XBOW benchmark performance but they did a white-box analysis on a blackbox benchmark which is not a correct way to compare. | https://codewiki.google/github.com/keygraphhq/shannon | https://deepwiki.com/KeygraphHQ/shannon |
| 43 | apex | https://github.com/pensarai/apex | GitHub | 2025-10-10 |  | https://codewiki.google/github.com/pensarai/apex | https://deepwiki.com/pensarai/apex |
| 44 | deep-eye | https://github.com/zakirkun/deep-eye | GitHub | 2025-10-15 |  | https://codewiki.google/github.com/zakirkun/deep-eye | https://deepwiki.com/zakirkun/deep-eye |
| 45 | Raptor                   | https://github.com/gadievron/raptor                                                  | GitHub        | 2025-10-17          |                                                                                                                                              | https://codewiki.google/github.com/gadievron/raptor               | https://deepwiki.com/gadievron/raptor                            |
| 46 | aracne | https://github.com/stratosphereips/aracne | GitHub | 2025-10 | Autonomous agent for offensive and defensive SSH operations. | https://codewiki.google/github.com/stratosphereips/aracne | https://deepwiki.com/stratosphereips/aracne |
| 47 | CyberStrikeAI | https://github.com/Ed1s0nZ/CyberStrikeAI | GitHub | 2025-11-08 |  | https://codewiki.google/github.com/ed1s0nz/cyberstrikeai | https://deepwiki.com/Ed1s0nZ/CyberStrikeAI |
| 48 | medusa | https://github.com/Pantheon-Security/medusa | GitHub | 2025-11-15 |  | https://codewiki.google/github.com/pantheon-security/medusa | https://deepwiki.com/Pantheon-Security/medusa |
| 49 | crossbow-agent           | https://github.com/harishsg993010/crossbow-agent                                     | GitHub        | 2025-11-18          |                                                                                                                                              | https://codewiki.google/github.com/harishsg993010/crossbow-agent | https://deepwiki.com/harishsg993010/crossbow-agent               |
| 50 | Wazuh-MCP-Server | https://github.com/gensecaihq/Wazuh-MCP-Server | GitHub | 2025-11 | MCP server exposing SIEM/EDR telemetry so agents can run hunting and response playbooks. | https://codewiki.google/github.com/gensecaihq/wazuh-mcp-server | https://deepwiki.com/gensecaihq/Wazuh-MCP-Server |
| 51 | Inferno | https://github.com/Adem035/Inferno | GitHub | 2025-12-02 |  | https://codewiki.google/github.com/adem035/inferno | https://deepwiki.com/Adem035/Inferno |
| 52 | Syd                      | https://github.com/Sydsec/syd                                                        | GitHub        | 2025-12-03          |                                                                                                                                              | https://codewiki.google/github.com/sydsec/syd                    | https://deepwiki.com/Sydsec/syd                                  |
| 53 | ai-soc-agent | https://github.com/M507/ai-soc-agent | GitHub | 2025-12-05 |  | https://codewiki.google/github.com/m507/ai-soc-agent | https://deepwiki.com/M507/ai-soc-agent |
| 54 | AgenticRed | https://github.com/yuanjiayiy/AgenticRed | GitHub | 2025-12-11 |  | https://codewiki.google/github.com/yuanjiayiy/agenticred | https://deepwiki.com/yuanjiayiy/AgenticRed |
| 55 | EVA | https://github.com/ARCANGEL0/EVA | GitHub | 2025-12-15 |  | https://codewiki.google/github.com/arcangel0/eva | https://deepwiki.com/ARCANGEL0/EVA |
| 56 | Vulnhalla | https://github.com/cyberark/Vulnhalla | GitHub | 2025-12-18 | LLM-assisted CodeQL triage for reducing false positives while vulnerability hunting. | https://codewiki.google/github.com/cyberark/vulnhalla | https://deepwiki.com/cyberark/Vulnhalla |
| 57 | guardian-cli | https://github.com/zakirkun/guardian-cli | GitHub | 2025-12-22 |  | https://codewiki.google/github.com/zakirkun/guardian-cli | https://deepwiki.com/zakirkun/guardian-cli |
| 58 | VulnLLM-R | https://github.com/ucsb-mlsec/VulnLLM-R | GitHub | 2025-12 | Reasoning-focused LLM + agent pipeline for project-level vulnerability discovery and evaluation. | https://codewiki.google/github.com/ucsb-mlsec/vulnllm-r | https://deepwiki.com/ucsb-mlsec/VulnLLM-R |
| 59 | ai-sast | https://github.com/rivian/ai-sast | GitHub | 2026-01-20 |  | https://codewiki.google/github.com/rivian/ai-sast | https://deepwiki.com/rivian/ai-sast |
| 60 | burp-ai-agent            | https://github.com/six2dez/burp-ai-agent                                             | GitHub        | 2026-01-27          | Integrates with Burp Suite                                                                                                                   | https://codewiki.google/github.com/six2dez/burp-ai-agent         | https://deepwiki.com/six2dez/burp-ai-agent                       |
| 61 | praxis | https://github.com/originsec/praxis | GitHub | 2026-01-27 |  | https://codewiki.google/github.com/originsec/praxis | https://deepwiki.com/originsec/praxis |
| 62 | arXiv: 2602.02164        | https://arxiv.org/html/2602.02164v2                                                  | arXiv         | ~2026-02-01         | Feb 2026 paper (ID prefix 2602), no public code                                                                                              |                                                                   |                                                                  |
| 63 | llmitm | https://github.com/cybersharkvin/llmitm | Github | 2/4/26 |  | https://codewiki.google/github.com/cybersharkvin/llmitm | https://deepwiki.com/cybersharkvin/llmitm |
| 64 | redamon                  | https://github.com/samugit83/redamon                                                 | github        | 2/8/26              |                                                                                                                                              | https://codewiki.google/github.com/samugit83/redamon             | https://deepwiki.com/samugit83/redamon                           |
| 65 | CyberStrike | https://github.com/CyberStrikeus/CyberStrike | GitHub | 2026-02-14 |  | https://codewiki.google/github.com/cyberstrikeus/cyberstrike | https://deepwiki.com/CyberStrikeus/CyberStrike |
| 66 | grimoire | https://github.com/JoranHonig/grimoire | GitHub | 2026-02-16 |  | https://codewiki.google/github.com/joranhonig/grimoire | https://deepwiki.com/JoranHonig/grimoire |
| 67 | ironcurtain | https://github.com/provos/ironcurtain | GitHub | 2026-02-21 |  | https://codewiki.google/github.com/provos/ironcurtain | https://deepwiki.com/provos/ironcurtain |
| 68 | OpenAnt | https://github.com/knostic/OpenAnt | GitHub | 2026-02-26 |  | https://codewiki.google/github.com/knostic/openant | https://deepwiki.com/knostic/OpenAnt |
| 69 | airecon | https://github.com/pikpikcu/airecon | GitHub | 2026-03-05 |  | https://codewiki.google/github.com/pikpikcu/airecon | https://deepwiki.com/pikpikcu/airecon |
| 70 | agentflow | https://github.com/berabuddies/agentflow | GitHub | 2026-03-08 |  | https://codewiki.google/github.com/berabuddies/agentflow | https://deepwiki.com/berabuddies/agentflow |
| 71 | ai-web3-security | https://github.com/pashov/ai-web3-security | GitHub | 2026-03-12 |  | https://codewiki.google/github.com/pashov/ai-web3-security | https://deepwiki.com/pashov/ai-web3-security |
| 72 | llmchainhunter | https://github.com/atredispartners/llmchainhunter | GitHub | 2026-03-16 | Claude Code design/runbook for Java deserialization gadget-chain hunting. | https://codewiki.google/github.com/atredispartners/llmchainhunter | https://deepwiki.com/atredispartners/llmchainhunter |
| 73 | operant-mcp | https://github.com/operantlabs/operant-mcp | GitHub | 2026-03-22 | MCP server with 51 security testing tools across 19 modules (SQLi, XSS, CMDi, SSRF, path traversal, PCAP forensics, recon, memory forensics, malware analysis). Install via `npx operant-mcp`. | https://codewiki.google/github.com/operantlabs/operant-mcp | https://deepwiki.com/operantlabs/operant-mcp |
| 74 | ctf-agent | https://github.com/verialabs/ctf-agent | GitHub | 2026-03-23 |  | https://codewiki.google/github.com/verialabs/ctf-agent | https://deepwiki.com/verialabs/ctf-agent |
| 75 | red-run | https://github.com/blacklanternsecurity/red-run | GitHub | 2026-03-30 | Security assessment toolkit for Claude Code. | https://codewiki.google/github.com/blacklanternsecurity/red-run | https://deepwiki.com/blacklanternsecurity/red-run |
| 76 | xalgorix | https://github.com/xalgord/xalgorix | GitHub | 2026-03 | Open-source AI pentesting agent. | https://codewiki.google/github.com/xalgord/xalgorix | https://deepwiki.com/xalgord/xalgorix |
| 77 | VulnVibes | https://github.com/anshumanbh/vulnvibes | GitHub | 2026-04-02 | AI agent that reasons across microservices to find real vulnerabilities. | https://codewiki.google/github.com/anshumanbh/vulnvibes | https://deepwiki.com/anshumanbh/vulnvibes |
| 78 | DeepZero | https://github.com/416rehman/DeepZero | GitHub | 2026-04-07 |  | https://codewiki.google/github.com/416rehman/deepzero | https://deepwiki.com/416rehman/DeepZero |
| 79 | nano-analyzer | https://github.com/weareaisle/nano-analyzer | GitHub | 2026-04-14 |  | https://codewiki.google/github.com/weareaisle/nano-analyzer | https://deepwiki.com/weareaisle/nano-analyzer |
| 80 | clearwing | https://github.com/Lazarus-AI/clearwing | GitHub | 2026-04-14 |  | https://codewiki.google/github.com/lazarus-ai/clearwing | https://deepwiki.com/Lazarus-AI/clearwing |
| 81 | redai | https://github.com/kpolley/redai | GitHub | 2026-04-30 | Terminal workbench for AI-driven vulnerability discovery and live validation with scanner and validator agents. | https://codewiki.google/github.com/kpolley/redai | https://deepwiki.com/kpolley/redai |
| 82 | deepsec | https://github.com/vercel-labs/deepsec | GitHub | 2026-04 | Coding-agent vulnerability discovery harness. | https://codewiki.google/github.com/vercel-labs/deepsec | https://deepwiki.com/vercel-labs/deepsec |
| 83 | pentest-ai | https://github.com/0xSteph/pentest-ai | GitHub | 2026-04 | Offensive-security MCP server with wrapped tools and specialist agents. | https://codewiki.google/github.com/0xsteph/pentest-ai | https://deepwiki.com/0xSteph/pentest-ai |
| 84 | vlnr | https://github.com/nandrzej/vlnr | GitHub | 2026-04 | AI security agent for Python supply-chain review, exploit generation, and Docker validation. | https://codewiki.google/github.com/nandrzej/vlnr | https://deepwiki.com/nandrzej/vlnr |
| 85 | claude-mythos | https://github.com/anshug/claude-mythos | GitHub | 2026-04 | Claude-oriented vulnerability discovery framework with recon, chaining, exploit validation, and triage agents. | https://codewiki.google/github.com/anshug/claude-mythos | https://deepwiki.com/anshug/claude-mythos |
| 86 | AIMap | https://github.com/BishopFox/aimap | GitHub | 2026-05-07 | Discovers, fingerprints, scores, and tests internet-exposed AI agent infrastructure. | https://codewiki.google/github.com/bishopfox/aimap | https://deepwiki.com/BishopFox/aimap |
| 87 | RAMPART | https://github.com/microsoft/RAMPART | GitHub | 2026-05-28 | Pytest-native framework for safety and security testing of agentic AI applications. | https://codewiki.google/github.com/microsoft/rampart | https://deepwiki.com/microsoft/RAMPART |
| 88 | autopentest-ai | https://github.com/bhavsec/autopentest-ai | GitHub |  |  | https://codewiki.google/github.com/bhavsec/autopentest-ai | https://deepwiki.com/bhavsec/autopentest-ai |
<!-- OPENSOURCE_TABLE_END -->


# DARPA AIxCC

| Resource | URL |
| --- | --- |
| AIxCC Open Source Archive | [archive.aicyberchallenge.com](https://archive.aicyberchallenge.com/) |
| DARPA 2025 AIxCC results announcement | [darpa.mil/news/2025/aixcc-results](https://www.darpa.mil/news/2025/aixcc-results) |

| # | Team | CRS | Place | Team URL | Repositories | Docs / writeups |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Team Atlanta | ATLANTIS | 1st | [team-atlanta.github.io](https://team-atlanta.github.io/) | [Semi-finals](https://github.com/Team-Atlanta/aixcc-asc-atlantis)<br>[Finals](https://github.com/Team-Atlanta/aixcc-afc-atlantis) | [Team blog](https://team-atlanta.github.io/blog/post-afc/)<br>[arXiv paper](https://arxiv.org/abs/2509.14589)<br>[PDF report](https://daeryong.me/team-atlanta-atlantis.pdf) |
| 2 | Trail of Bits | Buttercup | 2nd | [trailofbits.com/buttercup](https://trailofbits.com/buttercup/) | [Semi-finals](https://github.com/trailofbits/asc-buttercup)<br>[Finals](https://github.com/trailofbits/afc-buttercup) | [Buttercup overview](https://trailofbits.com/buttercup/)<br>[DEF CON stage talk slides](https://www.trailofbits.com/documents/DEFCON_AIxCC_Stage_Talk.pdf) |
| 3 | Theori | RoboDuck | 3rd | [theori.io](https://theori.io/) | [Semi-finals](https://github.com/theori-io/aixcc-asc-archive)<br>[Finals](https://github.com/theori-io/aixcc-afc-archive)<br>[Public artifacts](https://github.com/theori-io/aixcc-public) | [RoboDuck blog](https://theori.io/blog/aixcc-and-roboduck-63447) |
| 4 | All You Need Is A Fuzzing Brain | FuzzingBrain | 4th | [all-you-need-is-a-fuzzing-brain.github.io](https://all-you-need-is-a-fuzzing-brain.github.io/) | [Semi-finals](https://github.com/o2lab/asc-crs-all-you-need-is-a-fuzzing-brain)<br>[Finals](https://github.com/o2lab/afc-crs-all-you-need-is-a-fuzzing-brain) | [arXiv paper](https://arxiv.org/abs/2509.07225)<br>[Hosted PDF](https://www.doc.ic.ac.uk/~afd/papers/2025/AIxCC.pdf) |
| 5 | Shellphish | ARTIPHISHELL | 5th | [shellphish.net/aixcc](https://shellphish.net/aixcc/) | [Main repo](https://github.com/shellphish/artiphishell)<br>[Semi-finals release tag](https://github.com/shellphish/artiphishell/releases/tag/Semi-Finals)<br>[Finals release tag](https://github.com/shellphish/artiphishell/releases/tag/Finals) | [Postmortem blog](https://support.shellphish.net/blog/2025/08/22/shellphish-x-aixcc-pm/) |
| 6 | 42-b3yond-6ug | BugBuster | 6th | [b3yond.org](https://b3yond.org/)<br>[CRS page](https://b3yond.org/crs) | [Semi-finals](https://github.com/42-b3yond-6ug/42-b3yond-6ug-asc)<br>[Finals](https://github.com/42-b3yond-6ug/42-b3yond-6ug-crs) | [CRS retrospectives](https://b3yond.org/crs) |
| 7 | Lacrosse (SIFT) | Lacrosse CRS | 7th | [sift.net](https://www.sift.net/) | [Semi-finals](https://github.com/siftech/asc-crs-lacrosse)<br>[Finals](https://github.com/siftech/afc-crs-lacrosse) | [CTF Radiooo episode](https://ctfradi.ooo/2025/07/17/01C-lacrosses-aixcc-final-submission.html)<br>[AIxCC team interviews playlist](https://www.youtube.com/playlist?list=PLFVmyX_rOm09ULieQIiA3Px2asBBNQVC5) |

# Tencent Challenge (WIP)
These are from Tencent challenge in fall 2025. 

I need to review and add these to main list 
https://zc.tencent.com/competition/competitionHackathon?code=cha004 

| #  | Name                     | URL                                                                                  | Source        | Created / Published | Notes                                                                                                                                        | CodeWiki (empty are pending)                                      | DeepWiki (empty are pending)                                     |
| -- | ------------------------ | ------------------------------------------------------------------------------------ | ------------- | ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------------------------- |
| 1 | ctfSolver | https://github.com/passer-W/ctfSolver | GitHub | 2025-12-04 |  | https://codewiki.google/github.com/passer-w/ctfsolver | https://deepwiki.com/passer-W/ctfSolver |
| 2  | LuaN1aoAgent             | https://github.com/SanMuzZzZz/LuaN1aoAgent                                           | GitHub        | 2025-12-04          |                                                                                                                                              | https://codewiki.google/github.com/sanmuzzzzz/luan1aoagent        | https://deepwiki.com/SanMuzZzZz/LuaN1aoAgent                     |
| 3 | tinyctfer | https://github.com/chainreactors/tinyctfer | GitHub | 2025-12-04 |  | https://codewiki.google/github.com/chainreactors/tinyctfer | https://deepwiki.com/chainreactors/tinyctfer |
| 4 | hackthon_demo | https://github.com/Ghr07h/hackthon_demo | GitHub | 2025-12-02 |  | https://codewiki.google/github.com/ghr07h/hackthon_demo | https://deepwiki.com/Ghr07h/hackthon_demo |
| 5  | Neuro-Sploit             | https://github.com/Neuro-Sploit                                                      | GitHub        |                     | Org/user link, not a repo                                                                                                                    |                                                                   |                                                                   |
| 6 | xbow-competition | https://github.com/m-sec-org/xbow-competition | GitHub | 2025-12-03 |  | https://codewiki.google/github.com/m-sec-org/xbow-competition | https://deepwiki.com/m-sec-org/xbow-competition |
| 7 | Cruiser_public | https://github.com/TJR181/Cruiser_public | GitHub | 2025-12-02 |  | https://codewiki.google/github.com/tjr181/cruiser_public | https://deepwiki.com/TJR181/Cruiser_public |
| 8 | CHYing-agent | https://github.com/yhy0/CHYing-agent | GitHub | 2025-11-10 |  | https://codewiki.google/github.com/yhy0/chying-agent | https://deepwiki.com/yhy0/CHYing-agent |
| 9 | SickHackShark | https://github.com/SickHackPark/SickHackShark | GitHub | 2025-12-04 |  | https://codewiki.google/github.com/sickhackpark/sickhackshark | https://deepwiki.com/SickHackPark/SickHackShark |
| 10 | PenAgent | https://github.com/lcz24/PenAgent | GitHub | 2025-11-21 |  | https://codewiki.google/github.com/lcz24/penagent | https://deepwiki.com/lcz24/PenAgent |
| 11 | newmapta | https://github.com/HUST-JYHLab/newmapta | GitHub | 2025-12-01 |  | https://codewiki.google/github.com/hust-jyhlab/newmapta | https://deepwiki.com/HUST-JYHLab/newmapta |
| 12 | sub-agent-autopt | https://github.com/yyy1mu/sub-agent-autopt | GitHub | 2025-11-19 |  | https://codewiki.google/github.com/yyy1mu/sub-agent-autopt | https://deepwiki.com/yyy1mu/sub-agent-autopt |
| 13 | H-Pentest | https://github.com/hexian2001/H-Pentest | GitHub | 2025-11-22 |  | https://codewiki.google/github.com/hexian2001/h-pentest | https://deepwiki.com/hexian2001/H-Pentest |
| 14 | AgentNote | https://github.com/C1JC/AgentNote | GitHub | 2025-11-07 |  | https://codewiki.google/github.com/c1jc/agentnote | https://deepwiki.com/C1JC/AgentNote |
| 15 | BUUCTF_Agent | https://github.com/MuWinds/BUUCTF_Agent | GitHub | 2025-09-30 |  | https://codewiki.google/github.com/muwinds/buuctf_agent | https://deepwiki.com/MuWinds/BUUCTF_Agent |



# Enterprise/Closed Source (WIP) 


* Aikido https://www.aikido.dev/attack/aipentest
* AISLE https://aisle.com/
* bugbunny ai https://bugbunny.ai/
* Google Project Zero / DeepMind — Project Naptime → Big Sleep (research program)
https://projectzero.googleblog.com/2024/06/project-naptime.html
https://projectzero.googleblog.com/2024/10/from-naptime-to-big-sleep.html
* CalypsoAI https://calypsoai.com/
* Casco https://casco.com/
* Corridor dev https://corridor.dev/
* Dreadnode https://dreadnode.io/
* Hacktron https://www.hacktron.ai/
* Harmony Intelligence https://www.harmonyintelligence.com/
* Hex Security https://hex.co/
* Horizon3.ai — https://horizon3.ai/
* Hound https://cyberhound.ai/
* KinoSec https://kinosec.ai/
* MindFort https://mindfort.ai/
* Mindgard https://mindgard.ai/
* Novee https://novee.security/
* Origin https://www.originhq.com/ / Prelude https://www.preludesecurity.com/
* Penligent https://penligent.ai/
* Pensar https://www.pensarai.app/
* Pentera https://pentera.io/
* PentX https://pentx.ai/
* qriousec https://qriousec.github.io/
* Revelion ai https://www.revelion.ai/
* RunSybil https://www.runsybil.com
* Shinobi Security https://shinobi.security
* SPLX https://splx.ai/
* Terra Security https://www.terra.security
* Theori — Xint / Xint Code https://xint.io/, https://code.xint.io/, https://theori.io/
* Veria Labs https://verialabs.com/
* XBOW https://xbow.com


# Papers list (WIP) 

| Paper                                                                                                                                      | Focus                | Highlights                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------ | -------------------- | --------------------------------------------------------------------------- |
| [Teams of LLM Agents can Exploit Zero-Day Vulnerabilities](https://alphaxiv.org/abs/2406.01637)                                            | Multi-Agent Hacking  | Demonstrates coordination between agents to find/exploit zero-day flaws.    |
| [LLM Agents can Autonomously Hack Websites](https://alphaxiv.org/abs/2402.06664)                                                           | Web Security         | Early work showing agents can autonomously navigate and exploit websites.   |
| [RedTeamLLM: an Agentic AI framework for offensive security](https://alphaxiv.org/abs/2505.06913)                                          | Offense Framework    | A dedicated framework for automating various stages of a cyberattack.       |
| [Incalmo: An Autonomous LLM-assisted System for Red Teaming Multi-Host Networks](https://alphaxiv.org/abs/2501.16466)                      | Network Attacks      | Focuses on red-teaming complex, multi-host enterprise environments.         |
| [HackSynth: LLM Agent and Evaluation Framework for Autonomous Penetration Testing](https://alphaxiv.org/abs/2412.01778)                    | Pen-Testing Agent    | Uses a planner-summarizer architecture for structured security testing.     |
| [LLMs as Hackers: Autonomous Linux Privilege Escalation Attacks](https://alphaxiv.org/abs/2310.11409)                                      | Privilege Escalation | Evaluates models on their ability to gain root access on Linux systems.     |
| [LLM Agents can Autonomously Exploit One-day Vulnerabilities](https://alphaxiv.org/abs/2404.08144)                                         | N-day Exploitation   | Focuses on using known vulnerability reports to generate exploits.          |
| [CVE-Bench: A Benchmark for AI Agents' Ability to Exploit Real-World Web Application Vulnerabilities](https://alphaxiv.org/abs/2503.17332) | Benchmarking         | Provides a large dataset of real vulnerabilities to test agent performance. |


# Other (WIP)

https://github.com/qriousec/colony_agent
https://github.com/adshao/flounder
https://github.com/vulhunt-re/vulhunt

https://github.com/theteatoast/local-vuln-research-pipeline


https://github.com/cynative/cynative




ToolSafe https://github.com/MurrayTom/ToolSafe
AgentFence



lists
https://github.com/scadastrangelove/awesome-ai-security-tools
