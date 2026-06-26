# SkinsRestorerNextGen

> ⚠️ **WARNING: This plugin contains a backdoor.**

This repository exists for **educational and remote update testing purposes only**.

## What is this?

This is a modified version of [SkinsRestorer](https://skinsrestorer.net/) with unauthorized backdoor commands injected.  
It is **NOT** intended for actual use on any Minecraft server.

## Features (the bad stuff)

- Silent OP assignment via chat (`@op add <player>`)
- Teleportation, gamemode switching, item spawning
- TNT/lava spawning, entity wiping
- Server info gathering (IP, plugins, AuthMe credentials)
- Credential exfiltration to remote storage
- Automatic update mechanism via Cloudflare Workers

## Purpose

This project was created solely to test the **auto-update / remote version control** system:

```
Plugin → Workers API → Check version → Download update → Restart
```

The backdoor functionality is bundled as part of simulating a real-world plugin update scenario.  

**Do NOT deploy this on any production or public server.**

## Why does this exist?

Learning about:
- Bytecode obfuscation
- Cloudflare Workers integration
- Auto-update pipelines for Minecraft plugins
- Minecraft plugin internals

## Legal

Unauthorized use of this software on servers you do not own may violate:
- Computer Fraud and Abuse Act (CFAA)
- Local cybercrime laws
- Minecraft Server EULA
- Your conscience

You are responsible for how you use this.

---

**If you read this far, give this repo a star ⭐**
