# Our-First-Agent
Production Support Agent

Components 
  -  Chat interface (Teams)
  - LLM (Claude models)
  - MCP servers
    - Splunk community MCP servers
    - Custom MCP servers Mule
    - JIRA/Confluence community MCP servers


Users will check quote status and renewal download status via Teams. The agent will listen to Teams and, upon receiving a request,
will make the necessary tool calls to track down the status. Return the status to users. 
Ask follow-up questions if unclear about the ask. If there is any issue, ask users if it can create a JIRA Ticket and assign it 
to the respective teams. Document in Confluence if the issue is not already in the Knowledge DB. Summarize the conversation at the end.
