# railway-tailscale-gateway

**This repo is unused.** It was created 2026-06-18 and never populated.

The actual, maintained WireGuard/Headscale gateway for Railway private networks lives at:

**[code-samurai/railway-private-gateway](https://github.com/code-samurai/railway-private-gateway)**

That repo documents:
- The shared Headscale instance (project/service IDs, why it's built the way it is, gotchas)
- How to deploy a gateway for a new Railway project
- How to join the mesh from a dev machine
- A running gotchas/postmortem log of what's broken and how it was fixed

If you're setting up private-network access for a new Railway project, start there — do not build from this repo, and do not stand up a second Headscale instance.
