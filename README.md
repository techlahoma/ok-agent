# 200 OK Conference Vault

A collaborative knowledge base for the 200 OK Conference, built with Obsidian and Git.

## Quick Start

### For Speakers

#### Option A: Using Obsidian (Recommended)
1. Clone this repository:
   ```bash
   git clone https://github.com/techlahoma/200-ok-conference-vault.git
   ```
2. Open the folder in [Obsidian](https://obsidian.md)
3. Install the **Obsidian Git** plugin (Settings > Community Plugins > Browse)
4. Add your materials using the templates in `04-Templates/`

#### Option B: Using GitHub Web Interface
1. Navigate to `03-Content/speakers/` in this repository
2. Click "Add file" > "Create new file"
3. Name it `speaker-firstname-lastname.md`
4. Copy the content from `04-Templates/template-speaker.md`
5. Fill in your information and commit

### For Organizers

Full setup with auto-sync:

1. Clone the repository
2. Open in Obsidian
3. Install required plugins:
   - **Obsidian Git** - Auto-sync with GitHub
   - **Templater** - Template automation
   - **Dataview** (optional) - Dynamic queries
4. Configure Obsidian Git:
   - Vault backup interval: 60 minutes
   - Auto pull interval: 10 minutes
   - Pull changes before push: ON

### For Attendees

#### Query with AI
1. Download `_repomix-output/full-vault-rollup.md` from this repository
2. Upload to [Claude.ai](https://claude.ai) or ChatGPT
3. Ask questions like:
   - "What sessions are about AI?"
   - "Tell me about the speakers"
   - "What should I attend if I'm interested in data?"

#### Browse Locally
1. Clone the repository
2. Open in Obsidian as a read-only vault
3. Navigate using the [[000-Global-Index]]

## Folder Structure

```
200-OK-Conference-Vault/
├── README.md                    # You are here
├── 000-Global-Index.md          # Main navigation hub
├── 01-Primary-Categories/       # Top-level category pages
├── 02-Secondary-Categories/     # Sub-category pages
├── 03-Content/                  # Actual content
│   ├── sessions/                # Session notes
│   ├── speakers/                # Speaker bios
│   └── resources/               # Materials and references
├── 04-Templates/                # Note templates
├── 05-Personal/                 # Personal notes (git-ignored)
├── _repomix-output/             # AI-friendly rollup files
└── Attachments/                 # Images and files
```

## Adding Content

### Add a Session
1. Create a file in `03-Content/sessions/` named `session-your-topic.md`
2. Use the [[template-session]] as your starting point
3. Link to your speaker profile and any resources

### Add a Speaker Bio
1. Create a file in `03-Content/speakers/` named `speaker-firstname-lastname.md`
2. Use the [[template-speaker]] as your starting point
3. Add your headshot to `Attachments/`

### Add Resources
1. Create a file in the appropriate `03-Content/resources/` subfolder
2. Use [[template-resource]] as your starting point
3. For large files, host externally and link

## Automated Rollups

This repository automatically generates LLM-friendly rollup files via GitHub Actions:

- `full-vault-rollup.md` - Complete conference documentation
- `sessions-only.md` - Just session information
- `speakers-only.md` - Just speaker information

These are updated on every push to main.

## Contributing

1. Make sure you have the latest changes: `git pull`
2. Make your edits in Obsidian or any text editor
3. Commit and push your changes
4. The Obsidian Git plugin handles this automatically if configured

### Avoiding Conflicts
- Pull before making major edits
- Coordinate in Slack for significant changes
- Use `05-Personal/` for scratch work

## Need Help?

- **Slack:** #200ok on Techlahoma Slack
- **Email:** TBD
- **Issues:** Open a GitHub issue

## License

MIT License - See LICENSE file for details.
