# RASON MCP Server

[![MCPB release](https://img.shields.io/github/v/release/FrontlineSystems/rason-mcp-server?label=MCPB)](https://github.com/FrontlineSystems/rason-mcp-server/releases/latest)
[![RASON MCP (VS Code)](https://vsmarketplacebadges.dev/version/FrontlineSystems.rason-mcp.svg?label=RASON%20MCP%20%28VS%20Code%29)](https://marketplace.visualstudio.com/items?itemName=FrontlineSystems.rason-mcp)
[![RASON MCP (npm)](https://img.shields.io/npm/v/@frontlinesystems/rason-mcp-server?label=npm)](https://www.npmjs.com/package/@frontlinesystems/rason-mcp-server)

AI-powered platform for decision intelligence: building, analyzing, and solving optimization, simulation, data science, and decision models with RASON.

This repository is the **distribution channel** for the RASON MCP Server — Claude Desktop installs (`.mcpb`) live in [Releases](https://github.com/FrontlineSystems/rason-mcp-server/releases). The source code is maintained privately at [Frontline Systems](https://www.solver.com).

## Install

### Claude Desktop: drop-in extension

Grab the latest [MCPB release](https://github.com/FrontlineSystems/rason-mcp-server/releases/latest), then in Claude Desktop open **Settings → Extensions → Advanced Settings → Install Extension** and pick the file. On macOS you can also drag the `.mcpb` onto the app window. The install dialog offers to set a RASON bearer token, only needed to solve models or manage them in the cloud.

### Other clients

- **npm (any stdio MCP client)**: [`@frontlinesystems/rason-mcp-server`](https://www.npmjs.com/package/@frontlinesystems/rason-mcp-server)
- **VS Code**: [RASON MCP Server](https://marketplace.visualstudio.com/items?itemName=FrontlineSystems.rason-mcp) standalone, or [RASON Desktop](https://www.solver.com/rason-desktop) for the full bundle (RASON language server, local & cloud solvers, Power BI / Excel integration)

## What is RASON?

[RASON](https://www.solver.com/rason) (Restful Analytic Solver® Object Notation) is a multi-purpose modeling language and decision intelligence platform by [Frontline Systems](https://www.solver.com) for building, analyzing, and solving mathematical optimization, simulation / risk analysis, and data science / machine learning models, plus business decision rules and multi-stage decision flows.

The MCP server connects AI clients (Claude Desktop, VS Code Copilot, Cursor, Windsurf, Claude Code, and any other stdio MCP client) to RASON's modeling and solving capabilities — including a searchable library of ~200 example models, model templates, structural analysis, and result interpretation.

## Support

For questions, feedback, or licensing inquiries, contact your Frontline representative or reach us at [solver.com/how-may-we-help-you](https://www.solver.com/how-may-we-help-you).

## License

Copyright © 2026 Frontline Systems, Inc. All rights reserved. This is proprietary software; no part may be reproduced, distributed, or modified without prior written permission from Frontline Systems. See [LICENSE](LICENSE) for the full Frontline Systems Software License.
