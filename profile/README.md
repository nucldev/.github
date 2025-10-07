<img width="1920" height="1080" alt="Untitled design" src="https://github.com/user-attachments/assets/03603628-34bb-416e-87fb-e2b6d448688a" />

# Nucleus


**The modern game panel alternative**

Nucleus is a next-generation game server management panel built from the ground up to be faster, more intuitive, and more powerful than traditional solutions. If you've used Pterodactyl, Puffer, or CubeCoders, you'll feel right at home—just with a significantly better experience.

## Why we built Nucleus

Most game panels feel stuck in the past. They're complex when they should be simple, slow when they should be fast, and frustrating when they should just work. We created Nucleus because we believe managing game servers shouldn't require a PhD in system administration.

Nucleus brings modern web technologies and thoughtful UX design to game server management. Whether you're running a single server for friends or managing infrastructure for hundreds of clients, Nucleus scales with your needs without the complexity.

## What makes it different

**Modern interface**  
Built with contemporary web technologies that you'd actually want to use. Clean, fast, and intuitive.

**Performance focused**  
Every aspect is optimized for speed. From API responses to the dashboard, everything just feels snappy.

**Actually easy to use**  
Setup takes minutes, not hours. The interface makes sense. Documentation is clear. It just works.

**Secure by default**  
Enterprise-grade security isn't optional—it's built into every layer of Nucleus.

**Complete control**  
Self-hosted means your data stays yours. No vendor lock-in, no subscriptions, no compromises.

## Who uses Nucleus

**Hosting providers** can scale confidently with robust APIs and automation tools designed for multi-tenant environments.

**Community servers** get intuitive controls for managing players, installing mods, and configuring servers without touching the command line.

**Development teams** benefit from rapid deployment workflows and isolated test environments.

**Home lab enthusiasts** appreciate the minimal resource requirements and straightforward self-hosting.

## Core capabilities

Nucleus provides everything you need to manage game servers effectively:

- Unified dashboard for monitoring and managing all servers
- Granular resource allocation for CPU, RAM, storage, and network
- Role-based access control with fine-grained permissions
- Comprehensive REST API for automation and integrations
- Built-in file manager for editing configs and managing mods
- Real-time console access with command execution
- Automated backup system with one-click restoration
- Docker-based isolation for security and portability

## Project structure

Our ecosystem is split across several repositories:

**nucleus-panel** — Main panel application  
**nucleus-helion** - The backend used for the panel

## Getting started

Installation is straightforward. If you have Bun, Node.js installed, then just clone and run.

Nginx configuration are a bit to configure as it requires [PM2](https://pm2.keymetrics.io/) to run in the background.

The Helion backend is as easy to install, read through it's documentation to know how to install it manually or with npm.

Check out the [installation guide](https://github.com/nucldev/nucleus-panel) for detailed setup instructions and configuration options.

## Contributing

We welcome contributions from the community. Whether you're reporting bugs, suggesting features, or submitting code, your input helps make Nucleus better.

Report bugs and request features through [Issues](https://github.com/nucldev/nucleus-panel/issues). For broader discussions about the project's direction, join us in [Discussions](https://github.com/orgs/nucldev/discussions).

If you're contributing code, please review our [contribution guidelines](https://github.com/nucldev/.github/blob/main/CONTRIBUTING.md) first.

## License

Nucleus is open source software released under the MIT License.

## Connect

Get help, share your setup, or connect with other users:

[Discord](https://socials.nucleusdev.online/discord) • [Documentation](https://docs.nucleusdev.online/) • [Twitter](https://socials.nucleusdev.online/x) • [Email](mailto:support@nucleusdev.online)

---

Built by the Nucleus team and contributors worldwide.
