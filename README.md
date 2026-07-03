# OpenClaw Research Agent

An automated AI research assistant built on the OpenClaw orchestration framework. This agent manages continuous data discovery, literature synthesis, and cross-platform notification pipelines across two main research tracks:

### 1. Longitudinal Autism Research Tracker
* **Frequency:** Weekly evaluation cycle.
* **Workflow:** Monitors, aggregates, and synthesizes newly released literature on autism spectrum disorders published within the trailing 7 days.
* **Output:** Generates a compiled PDF summary report and broadcasts it automatically to a designated Discord channel.

### 2. AI Development Knowledge Base & Daily Digest
* **Frequency:** Daily data collection with weekly synthesis.
* **Workflow:** Conducts daily scrapes of AI development research papers, preprints, and media articles. Extracted data points are systematically committed to the agent's long-term memory tier. 
* **Output:** On a weekly cadence, the agent aggregates the historical data from its local memory to construct an automated executive summary. The final analytics report is formatted as a PDF and dispatched to Discord.
