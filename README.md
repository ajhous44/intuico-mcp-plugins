# Intuico Digital MCP plugins

First-party hosted MCP connectors maintained by Intuico Digital, LLC:

| Plugin | Product | Scope |
| --- | --- | --- |
| AutoFire | https://www.goautofire.com | Read-only authorized dealership data |
| UniPost | https://unipost.ai | Workspace social publishing with approval |
| Calorie Cub | https://caloriecub.com | Private food diary, recipes, goals and weight |

Each package contains only metadata, documentation, optional skills and a hosted server URL. No local executables, hooks, dependencies or credentials are included. Sign in with each service using its OAuth flow and revoke access in that service's settings. Never paste a password or token into chat.

## Review

The packages are submitted for review; this repository does not imply marketplace approval. Public setup instructions and privacy/terms links are in each plugin README. For an isolated sample-data reviewer account or dealership, contact aj@intuicodigital.com. Do not connect real customer or personal health data for review.

All three xAI catalog entries passed its local catalog and generated-index checks. AutoFire profile/inventory and UniPost account listing were verified in-app. Calorie Cub's 19 production tools were tested with synthetic data through official MCP Inspector, with additional OAuth discovery in Claude and OpenAI.

## Licensing

AutoFire plugin files retain their upstream MIT license. UniPost and Calorie Cub carry Proprietary metadata as in their existing public submissions. The hosted services have their own terms and privacy policies; their application source code is not included here.
