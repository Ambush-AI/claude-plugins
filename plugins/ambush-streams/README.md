# Ambush Streams

Ambush Streams lets Claude Code create and manage personalized news streams.
The plugin combines workflow guidance with the production Ambush OAuth MCP
server for stream discovery, creation, updates, per-event post-processing,
delivery routing, pause and resume, permanent deletion, and emission review.

## Example requests

- "Create a stream for material cybersecurity incidents affecting Canadian banks."
- "Pause my AI regulation stream."
- "Show the five latest items from my semiconductor supply-chain stream."
- "For every event from that stream, produce a trade thesis or no-trade result and send it to my Trade Ideas Slack channel."

The MCP API retains legacy tool identifiers internally. Claude uses those exact
identifiers while referring to the resources as streams in conversation.
