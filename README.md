<p align="center">
  <img src="https://n2osync.com/logo-square.png" alt="N2O" width="120" />
</p>

<h1 align="center">N2O - Notion to Obsidian Sync</h1>

<p align="center">
  <strong>True bidirectional sync between Notion and Obsidian.</strong><br/>
  Your knowledge, everywhere.
</p>

<p align="center">
  <a href="https://n2osync.com">Website</a> · 
  <a href="https://n2osync.com/docs">Docs</a> · 
  <a href="https://simhaxdev.gumroad.com/l/n2opro">Get Pro</a> · 
  <a href="https://github.com/n2osync/n2o/issues">Report a Bug</a>
</p>

---

<!-- TODO: Add hero screenshot or GIF here showing Notion + Obsidian side by side -->

## The Problem

You use Notion at work. Your team lives there - project boards, meeting notes, shared wikis. But your personal notes, your second brain, that lives in Obsidian. And right now, these two worlds don't talk to each other.

You're copy-pasting. You're exporting markdown that breaks. You're maintaining two separate copies of the same knowledge.

**N2O fixes that.**

## What N2O Does

- **Bidirectional sync** - changes flow both ways, Notion to Obsidian and back
- **Full content support** - all 27+ block types, 21 property types, rich text formatting
- **Database mapping** - Notion databases become Obsidian folders with frontmatter
- **Relations to Wikilinks** - Notion relations become Obsidian `[[backlinks]]`
- **Attachment sync** - images and files downloaded locally to your vault
- **Three-way merge** - when both sides change the same page, N2O merges them. You never lose data
- **Incremental sync** - only changed pages are re-fetched. Fast, even with large workspaces
- **100% local** - direct Notion API calls. No third-party servers. No cloud. Your data never leaves your machine

---

## Quick Start

### Via BRAT (Recommended)

N2O is in pre-release. Install with [BRAT](https://github.com/TfTHacker/obsidian42-brat):

1. Install **BRAT** from Obsidian's Community Plugins
2. Open BRAT settings > **Add Beta Plugin**
3. Enter: `https://github.com/n2osync/n2o`
4. Done. BRAT keeps it updated automatically.

### Manual Install

1. Download `main.js`, `manifest.json`, `styles.css`, and `sql-wasm.wasm` from the [latest release](https://github.com/n2osync/n2o/releases/latest)
2. Create `.obsidian/plugins/n2o/` in your vault
3. Copy all four files into that folder
4. Restart Obsidian, enable N2O in Community Plugins

---

## How It Works

| Action | Direction | What it does |
|--------|-----------|-------------|
| **Sync Now** | Notion > Obsidian | Pulls pages and writes them as Markdown |
| **Push Changes** | Obsidian > Notion | Sends your local edits back to Notion |
| **Preview** | - | Dry-run showing what would change |

**Pro automation:** Auto-sync on a timer, real-time fast polling, and auto-push on local edits.

When both Notion and Obsidian change the same page, N2O does a three-way merge using a stored base version. No data lost on either side.

<!-- TODO: Add 2-3 screenshots here: Dashboard, Database mapping, Conflict resolution -->

---

## Free vs Pro

N2O is fully functional on the free tier. Pro just removes limits and adds automation.

| Feature | Free | Pro |
|---------|:----:|:---:|
| Synced pages | 100 | Unlimited |
| Databases | Unlimited | Unlimited |
| All block types & properties | Yes | Yes |
| Three-way merge | Yes | Yes |
| Pull sync (Notion > Obsidian) | Yes | Yes |
| Push sync (Obsidian > Notion) | - | Yes |
| Auto-sync & scheduling | - | Yes |
| Fast polling (near real-time) | - | Yes |
| Auto-push (live bidirectional) | - | Yes |
| Custom templates | - | Yes |

**Pro:** [$8/month](https://simhaxdev.gumroad.com/l/n2opro) or [$249 lifetime](https://simhaxdev.gumroad.com/l/n2oprolife)

> 14-day free trial. 300 pages, no credit card required. Start from plugin settings.

---

## Why I Built This

I kept two separate copies of everything - one in Notion for my team, one in Obsidian for myself. Every week I'd spend time manually syncing them. N2O started as a script to automate that. It grew into something that handles databases, properties, attachments, conflicts, and everything else that makes syncing between two very different apps hard.

If you use both Notion and Obsidian, this was built for you.

---

## Privacy & Security

- All sync data stays **local** in your Obsidian vault
- N2O talks directly to the **Notion API**, no intermediary servers
- **Zero telemetry**, analytics, or tracking
- License activation via Gumroad, no other third-party services
- Open source under MIT license

[Privacy Policy](https://n2osync.com/privacy) · [Terms of Service](https://n2osync.com/terms)

---

## Support

- **Docs** - [n2osync.com](https://n2osync.com)
- **Email** - support@n2osync.com
- **Issues** - [GitHub Issues](https://github.com/n2osync/n2o/issues)

---

<p align="center">
  Ready to try it? Install via BRAT in under a minute. Free, no account required.
</p>
