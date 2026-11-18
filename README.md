## Hi, I'm James

I build systems that make other systems talk to each other. Most of my work lives in the seams between services: messaging, webhooks, workflows, and everything that has to go right for a message to survive the trip.

I was the founding engineer at [Zapier](https://zapier.com), where I built and ran production engineering. My own projects are mostly Elixir these days, and I write about event-driven architecture and agentic development at [james-carr.org](https://james-carr.org).

### What I'm building

- [Ankusa](https://github.com/jamescarr/ankusa) is open-source webhook ingestion. It verifies each webhook and writes it to durable storage before the provider gets its `2xx`, then delivers it to Kafka, RabbitMQ, NATS JetStream, SQS, Google Pub/Sub, Redis, or plain HTTP, with retries, a dead-letter queue, and replay.
- [tinderbox](https://github.com/jamescarr/tinderbox) is an [Igniter](https://hexdocs.pm/igniter) template that scaffolds an Elixir API, a Broadway worker, or a Phoenix LiveView SaaS app, plus the local tooling to run it.
- [diagram-skill](https://github.com/jamescarr/diagram-skill) is an Agent Skill that draws Excalidraw architecture diagrams in [Enterprise Integration Patterns](https://www.enterpriseintegrationpatterns.com/) notation.
- [ABRAXAS](https://github.com/jamescarr/abraxas) is a 1999 BBS hacker game for the terminal, written in Rust, that dreams its own levels.

### Writing

Latest posts from [james-carr.org](https://james-carr.org):

<!-- BLOG-POST-LIST:START -->
- [My Plan Loop: Spinning Up Agents to Run a Checklist](https://james-carr.org/posts/2026-10-24-my-plan-loop-spinning-up-agents-to-run-a-checklist/)
- [What I Actually Use Jev For](https://james-carr.org/posts/2026-10-13-what-i-actually-use-jev-for/)
- [Building Your Own Advisors in Oh My Pi](https://james-carr.org/posts/2026-10-02-building-your-own-advisors-in-oh-my-pi/)
- [Current Agentic Development Environment: Orca + Oh My Pi](https://james-carr.org/posts/2026-09-30-current-agentic-development-setup-orca-oh-my-pi/)
- [Through the Gates of Angkor Thom, to Bayon](https://james-carr.org/posts/2026-08-17-through-the-gates-of-angkor-thom-to-bayon/)
<!-- BLOG-POST-LIST:END -->

Two series come with code you can run:

- [Advent of Enterprise Integration Patterns](https://james-carr.org/posts/2025-12-15-advent-of-enterprise-integration-patterns/) is a 12-day walk through the patterns that builds [chronicle](https://github.com/jamescarr/chronicle), an audit log in Gleam.
- [Temporal Patterns](https://james-carr.org/posts/2026-01-29-temporal-workflow-orchestration/) covers sagas, process managers, and scatter-gather in [night-city-services](https://github.com/jamescarr/night-city-services).

### Elsewhere

[Bluesky](https://bsky.app/profile/james-carr.org) · [LinkedIn](https://www.linkedin.com/in/jamesfreakincarr/) · [Mastodon](https://mastodon.sdf.org/@jamescarr) · [X](https://twitter.com/jamescarr) · [RSS](https://james-carr.org/posts/index.xml)
