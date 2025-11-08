# DazzleProj

**System Management, Simplified**

[![GitHub](https://img.shields.io/badge/GitHub-DazzleProj-blue?logo=github)](https://github.com/DazzleProj)
[![Sponsor](https://img.shields.io/badge/Sponsor-GitHub-ea4aaa?logo=github-sponsors)](https://github.com/sponsors/djdarcy)
[![License](https://img.shields.io/badge/License-GPL%203.0%20%2F%20MIT-green.svg)](LICENSE)

> A cohesive ecosystem of system management tools, utilities, and automation designed to make managing your computers easier, more reliable, and more consistent across all platforms.

---

## What is Dazzle?

**DazzleProj** is an open-source collection of system management tools built on the principle that we all want better tools for managing our computers—whether you're organizing your home files, managing an IT infrastructure, or setting up consistent development environments.

Born from years of managing multiple machines and solving real-world system management challenges, Dazzle provides:

- **File Management** - Backup, verify, and organize files with confidence
- **Cross-Platform Tools** - Same commands work on Windows, Linux, and macOS
- **System Setup** - Consistent environment across all your machines
- **AI Integration** - Modern AI-assisted workflows for productivity
- **Automation** - Script complex tasks with reliable, tested tools

**Organized as five GitHub organizations** (DazzleProj, DazzleLib, DazzleTools, DazzleNodes, DazzleML) - similar to how the Linux project coordinates the kernel, libraries, utilities, and applications under one umbrella.


### Project Status

| Organization | Status | Description |
|-----------|--------|-------------|
| [DazzleProj](https://github.com/DazzleProj) | 📋 Planning | Build environment repository migration in progress |
| [DazzleTools](https://github.com/DazzleTools) | 🚧 Active Development | 20+ tools ready, 100+ developed but not released |
| [DazzleLib](https://github.com/DazzleLib) | ✅ Stable | Published on PyPI, actively used |
| [DazzleNodes](https://github.com/DazzleNodes) | ✅ Active | Published on ComfyUI Registry |
| [DazzleML](https://github.com/DazzleML) | 🚧 Active Development | New tools being developed |

---

### Who is Dazzle For?

**🏠 Home Users**
- Back up important files with verification
- Organize large photo/video collections
- Keep multiple computers in sync
- Manage files across network drives

**💼 IT Professionals**
- Automate system setup and configuration
- Manage files across multiple servers
- Verify data integrity after transfers
- Deploy consistent tool environments

**👨‍💻 Developers**
- Set up development environments consistently
- Manage code repositories and assets
- Automate build and deployment tasks
- Integrate AI tools into workflows

**🎨 Content Creators**
- Organize project files and assets
- Back up work with verification
- Manage large media libraries
- Streamline ComfyUI workflows

### Philosophy

Managing systems shouldn't require reinventing the wheel or remembering obscure commands. Dazzle tools follow these principles:

1. **Works Everywhere** - Windows, Linux, macOS—same tools, same commands
2. **Simple but Powerful** - Easy for beginners, powerful for experts
3. **Reliable** - Verification built in, so you know operations succeeded
4. **Scriptable** - Automate anything, integrate with existing workflows
5. **Open Source** - Transparent code, community-driven improvements

### History

After years of managing systems and solving recurring problems at Microsoft and beyond, I started building a personal collection of tools. What began as quick scripts evolved into polished utilities that solve real problems for real people. 

**Today**, Dazzle powers home networks, IT infrastructures, and development workflows—making system management easier for everyone.

---

## The Dazzle Ecosystem

Dazzle is organized into **five specialized GitHub organizations**:

### Think of it like Linux

Similar to how the Linux project includes the kernel, GNU tools, system utilities, and distributions—all coordinated under the "Linux" umbrella—**DazzleProj** serves as the coordinating organization that ties everything together:

- **DazzleProj** = The overarching project (like "Linux" itself)
  - Home of the build environment (setenv.cmd/sh/py)
  - File structure standards
  - Cross-platform consistency layer

- **DazzleLib** = Foundation libraries (like glibc, core system libraries)
- **DazzleTools** = System utilities (like GNU coreutils, findutils)
- **DazzleML** = Specialized tools (like AI/ML tooling ecosystem)
- **DazzleNodes** = Application extensions (like desktop environments, plugins)

Just as you might install "Linux" and get a complete system, DazzleProj aims to provide one setup command that installs and configures your entire tool environment across any platform.

---

### 🔧 [DazzleTools](https://github.com/DazzleTools)
**Practical utilities for everyday tasks**

Hundreds of tools developed over multiple decades, with 20+ ready for public release.

From the extensive collection in `WinTools/`, `NixTools/`, and `OmniTools/` directories, we're selectively publishing the most stable and widely-useful tools first.

#### ⭐ Some Popular Tools

1. **[NCSI Resolver](https://github.com/djdarcy/Windows-No-Internet-Secured-BUGFIX)** - Fix Windows "No Internet, Secured" false detection
   - One-click solution to Windows connectivity bug making OneNote & other MS UWP apps work again
   - Runs silently in background as Windows service
   - Helpful for Windows users with smart firewalls/routers
   - *"Windows says 'No Internet' but you know better"*

2. **[process-delta](https://github.com/djdarcy/process-delta)** - Snapshot and manage running processes/services
   - Capture system state before/after changes
   - Automate startup optimizations
   - Free up resources for gaming or intensive work
   - *"Stop all unnecessary services with one command for gaming; or startup for virtual desktops"*

3. **[preserve](https://github.com/djdarcy/preserve)** - Back up files with verification and restore
   - Automatic file integrity verification (SHA256, etc.)
   - Multiple backup strategies (flat, relative, absolute paths)
   - One-command restoration to original locations
   - *"Back up 50GB of photos and verify nothing corrupted and restore to original location"*

4. **[listall](https://github.com/djdarcy/listall)** - Advanced directory listing and analysis
   - Detailed file and directory information
   - Filter and search capabilities
   - Export to various formats (including JSON style-output)
   - *"Analyze what's taking up space on my drive"*

5. **[open-ports-and-programs](https://github.com/djdarcy/open-ports-and-programs)** - Network diagnostics
   - See what programs are using which ports
   - Identify network activity and connections
   - Security auditing
   - *"What program is using port 80?"*

#### Other Tools
- **[git-repokit](https://github.com/djdarcy/git-repokit)** - Manage creating git and Github/Gitlab/etc repositories
- **[dazzlelink](https://github.com/djdarcy/dazzlelink)** - Smart file referencing and organization
- **[dazzlesum](https://github.com/djdarcy/dazzlesum)** - Calculate and verify checksums
- **[pattern-break](https://github.com/djdarcy/pattern-break)** - Pattern matching and transformation
- **[folder-datetime-fix](https://github.com/djdarcy/folder-datetime-fix)** - Fix incorrect file/folder dates
- **[temp-renamer](https://github.com/djdarcy/temp-renamer)** - Temporary file renaming utility
- **[discord-cleanup](https://github.com/djdarcy/discord-cleanup)** - Discord channel cleanup tool
- Plus more utilities

**License**: Primarily GPL3, some proprietary tools available

**Note**: Tools are currently at https://github.com/djdarcy and will be migrated to DazzleTools organization

---

### 📚 [DazzleLib](https://github.com/DazzleLib)
**Building blocks that power Dazzle tools**

Reliable libraries for file operations and system tasks:
- **[dazzle-filekit](https://github.com/DazzleLib/dazzle-filekit)** - Cross-platform file operations with verification
- **[dazzle-tree-lib](https://github.com/djdarcy/dazzle-tree-lib)** - Work with hierarchical data structures
- **[UNCtools](https://github.com/djdarcy/UNCtools)** - Handle Windows network paths correctly

**License**: Mostly MIT (can be used in any project)

**Note**: Most users don't need to install these directly—they're available through PyPi and included automatically with tools that use them.

---

### 🎨 [DazzleNodes](https://github.com/DazzleNodes)
**Extensions for ComfyUI image generation**

Custom nodes that make ComfyUI workflows easier:
- **[Smart Resolution Calculator](https://github.com/djdarcy/ComfyUI-Smart-Resolution-Calc)** - Automatic aspect ratio handling
- **[Fit Mask to Image](https://github.com/DazzleNodes/fit-mask-to-image)** - Auto-match mask dimensions
- More nodes in development

**License**: Mostly MIT (ComfyUI compatible)

**Use Cases**:
- "I want smarter resolution controls in ComfyUI"
- "I need masks to automatically match my images"

---

### 🤖 [DazzleML](https://github.com/DazzleML)
**AI-assisted tools and workflows**

1. **[ComfyUI Triton & SageAttention Installer](https://github.com/djdarcy/comfyui-triton-and-sageattention-installer)** - One-click setup for advanced AI features
   - Automatic installation of Triton and SageAttention optimizations
   - Significant speed improvements for ComfyUI image generation
   - Handles complex CUDA dependencies automatically
   - *"Get 2-3x faster ComfyUI generation with one command"*
2. **[AI Training Monitor](https://github.com/djdarcy/ai-training-monitor)** - Track and visualize AI training sessions
   - Real-time monitoring of training progress
   - Loss curve visualization
   - Resource usage tracking
   - *"Keep an eye on your overnight training runs"*

#### Other AI Tools
- **[MCP-Server-Tutorial](https://github.com/djdarcy/MCP-Server-Tutorial)** - Guides for Model Context Protocol integration
- **[find-best-images](https://github.com/djdarcy/find-best-images)** - AI-powered image curation and selection
- **[forks](https://github.com/djdarcy/forks)** - AI-related utilities and experiments

#### 🔗 TodoAI Integration
DazzleML tools are designed to integrate with **[TodoAI](https://github.com/Todo-AI)**, a separate project building a task-based operating system. TodoAI consumes DazzleML tools to provide AI-assisted task management and intelligent workflow automation.

**License**: GPL3

**Note**: Tools are currently at https://github.com/djdarcy and will be organized under DazzleML

---

### 🏗️ [DazzleProj](https://github.com/DazzleProj) - Build Environment
**One command to set up your entire system**

**DazzleProj** is both the ecosystem coordinator AND a GitHub organization in its own right—the home of the Dazzle build environment.

**Repository**: The current build environment at https://github.com/djdarcy/dazzle will be migrated to https://github.com/DazzleProj/dazzle

**The Vision**: Type one command, and your computer is configured with all your tools, settings, and preferences—whether it's a new machine, a fresh install, or just keeping multiple computers in sync.

**Current State**:
- `setenv.cmd` - Working Windows environment setup (in active use)
- `setenv.sh` - Linux/macOS version in development
- `setenv.py` - Future cross-platform unified solution

**Goal**: Like installing a Linux distribution, but for your personal tool environment—uniform setup where the same tools work the same way on every machine you use.

**Why It's Complex**:
- Works with network drives, local drives, portable drives
- Handles different directory structures
- Manages many tools and their configurations
- Needs to be simple to use but flexible for different setups
- Must coordinate installation of DazzleTools, DazzleLib, DazzleNodes, and DazzleML

**Status**: Packaging and distribution strategy in development. May be funded through community support to properly solve these challenges.

---

## Quick Start

### Installation

Most Dazzle tools will be available via pip (Python package manager):

```bash
# Install file backup and management tool
pip install dazzle-preserve

# Install checksum verification tool
pip install dazzlesum

# Install file organization libraries
pip install dazzle-filekit
```

For ComfyUI nodes:
```bash
cd ComfyUI/custom_nodes
git clone --recursive https://github.com/DazzleNodes/DazzleNodes.git
```

**Don't have Python?** Don't worry -- installation guides for beginners coming soon on [DazzleProj.com](https://dazzleproj.com)

### Common Tasks

**Back up your important files:**

```bash
# Simple backup with verification
preserve COPY --src "%USERPROFILE%\\My Documents" --dst "E:/Backup" --recursive

# Backup preserving full paths
preserve COPY --src "%USERPROFILE%\\Pictures" --dst "E:/Backup" --abs --recursive
```

**Verify your backup worked correctly:**

```bash
# Check that files match exactly
preserve VERIFY --src "%USERPROFILE%\\Pictures" --dst "E:/Backup" --hash SHA256
```

**Calculate checksums for important files:**
```bash
# Create checksum file to verify later
dazzlesum calculate /path/to/files --algorithm sha256 --output checksums.txt
```

**Restore files to original locations:**
```bash
# Restore from backup
preserve RESTORE --src "E:/Backup"
```

See individual project documentation for more examples and advanced usage.

---

## Real-World Use Cases

### Home Use

**Scenario**: "I have 50GB of family photos on my computer. I want to back them up to an external drive and make sure nothing corrupted during the copy."

```bash
# Back up with verification
preserve COPY --src "C:/Family Photos" --dst "E:/Backup" --recursive --hash SHA256

# Later, verify the backup is still good
preserve VERIFY --src "E:/Backup" --hash SHA256
```

**Time saved**: Manual copying + verification = 2-3 hours. With Dazzle = 10 minutes active time.

---

### IT Management

**Scenario**: "I need to deploy the same set of tools to 50 workstations with minimal effort."

```bash
# On each machine (or via script):
pip install dazzle-preserve dazzlesum dazzle-filekit

# Or use Dazzle build environment (future):
setenv.py --profile "corporate-workstation"
```

**Time saved**: Manual installation per machine = 30 min × 50 = 25 hours. With Dazzle = 1 hour scripting + 5 min per machine = 5 hours.

---

### Developer Workflows

**Scenario**: "I work on 3 different computers (home desktop, laptop, work machine). I want the same tools available everywhere."

```bash
# On each machine:
git clone https://github.com/djdarcy/dazzle-config
cd dazzle-config
./setup.sh  # Installs all your preferred tools
```

**Time saved**: Manual setup per machine = 2-4 hours × 3 = 6-12 hours. With Dazzle = 15 minutes per machine = 45 minutes.

---

### Content Creation

**Scenario**: "I have 10,000 images from a photo shoot. I need to find the best ones and organize them into folders by subject."

```bash
# AI-powered image curation
find-best-images --src "/photo-shoot" --criteria "sharpness,composition" --top 100

# Then organize
preserve COPY --loadIncludes "best-images.txt" --dst "/final-selection" --rel
```

**Time saved**: Manual review = 20-30 hours. With Dazzle = 2-3 hours.

---

## System Requirements

**Operating Systems**:
- ✅ Windows 10/11
- ✅ Linux (Ubuntu, Debian, Fedora, etc.)
- ✅ macOS 11+

**Prerequisites**:
- Python 3.8 or newer (most systems have this)
- pip (Python package manager, included with Python)

**Optional**:
- Git (for source installation)
- ComfyUI (for DazzleNodes)

---

## Architecture Overview

```
DazzleProj (Ecosystem coordinator + Build Environment)
│
├── Build Environment Repository
│   └── setenv.* → Installs and configures everything below
│
├── DazzleLib (Foundation - github.com/DazzleLib)
│   ├── dazzle-filekit → Used by most tools
│   ├── dazzle-tree-lib → Hierarchical data
│   └── UNCtools → Windows network paths
│
├── DazzleTools (Utilities - github.com/DazzleTools)
│   ├── preserve → Uses dazzle-filekit
│   ├── dazzlelink → Uses dazzle-filekit
│   ├── dazzlesum → File verification
│   ├── process-delta → System management
│   ├── ncsi-resolver → Network diagnostics
│   └── 100+ more tools (selective publication)
│
├── DazzleML (AI Tools - github.com/DazzleML)
│   ├── comfyui-triton-installer → Most popular Dazzle project
│   ├── ai-training-monitor
│   ├── find-best-images
│   └── AI workflow tools
│
└── DazzleNodes (ComfyUI - github.com/DazzleNodes)
    ├── smart-resolution-calc
    └── fit-mask-to-image
```

**Five Organizations = Five Specialized Areas**, all coordinated through DazzleProj

---

## Licensing

Dazzle uses a practical licensing approach:

### Open Source Core
- **DazzleLib** (MIT): Use in any project, commercial or not
- **DazzleTools** (GPL3): Free for everyone, keeps tools open
- **DazzleNodes** (MIT): Compatible with ComfyUI ecosystem
- **DazzleML** (GPL3): Encourages open AI tooling

### Commercial Options
Some specialized DazzleTools have commercial licenses for businesses. These are:
- Clearly marked in documentation
- Have free alternatives for personal use
- Help fund continued development

**Simple rule**: If you're a home user or small team, everything is free. Businesses using some specialized tools may need commercial licenses.

---

## Related Projects

### [ZeroMeld](https://github.com/ZeroMeld)
Open-source CRM for managing social media and community discussions
- Monitor Reddit, forums, and discussion boards
- Turn posts into actionable cases
- Great for nonprofits, community managers, customer support

### [TodoAI](https://github.com/Todo-AI)
Task-based operating system with AI integration - **Active development with production-ready codebase**

**Current Projects**:

1. **[TodoAI-Todoist](https://github.com/Todo-AI/TodoAI-Todoist)** *(Coming Soon)*
   - Enhanced MCP server for Todoist with AI capabilities
   - Local caching for instant task searches
   - Smart priority mapping and advanced filtering
   - 60+ unit tests, production-ready
   - Designed for Claude Code and AI assistants
   - Complete CRUD for tasks, projects, labels, sections, comments

2. **[TodoAI-Todoist-Notepad](https://github.com/Todo-AI/TodoAI-Todoist-Notepad)** *(Coming Soon)*
   - Cross-platform Flutter/Dart notepad for Todoist
   - Natural text syntax: type like a notepad, sync automatically
   - Works on Windows, Mac, Linux, iOS, Android
   - Agentic behavior: type and things happen automatically
   - Offline support with real-time sync
   - Smart widgets for dates, labels, project navigation

**Vision**: Tasks as the fundamental unit of computing - a task-based operating system where AI and human work converge through natural language task management.

**Integration**: Consumes DazzleML tools for intelligent workflow automation

---

## Contributing

Dazzle welcomes contributions from everyone! Whether you're fixing a typo, reporting a bug, or building a new tool, your help is appreciated.

### Easy Ways to Help

1. 🐛 **Report bugs** - Found something broken? Let us know!
2. 💡 **Suggest features** - Have an idea? Share it!
3. 📝 **Improve docs** - Help make documentation clearer
4. ⭐ **Star repos** - Show support and increase visibility
5. 💬 **Share** - Tell others who might find Dazzle useful

### Contributing Code

1. Pick a project that interests you
2. Fork the repository on GitHub
3. Make your improvements
4. Test thoroughly
5. Submit a pull request

Each project has specific contribution guidelines in its repository.

---

## 💰 Sustainability

**Current Reality**: Dazzle development happens in free time at personal expense.

**Current sponsorship: $0/month**
**Goal: $1,000/month** to maintain and improve tools

### Why This Matters

These tools represent thousands of hours of development, testing, and support over multiple decades:
- **preserve** alone saves users 5-10 hours per month in manual file management
- **dazzlesum** prevents data corruption that could lose irreplaceable files
- **Dazzle build environment** (future) easily saves 4+ hours per machine setup measured from personal use with `setenv`

**At $50/hour value**, a single tool saves **$250-500/month** in time.

Contributing **$10-50/month** is a small fraction of the value received from the full Dazzle suite.

### How to Help

**💵 Sponsor on GitHub**: [github.com/sponsors/djdarcy](https://github.com/sponsors/djdarcy)

**Sponsor Tiers**:

- 🌟 $5/month - Supporter (Name in credits)
- 🌟🌟 $25/month - Contributor (Logo on website)
- 🌟🌟🌟 $100/month - Bronze (Priority support)
- 🌟🌟🌟🌟 $500/month - Silver (2hrs consulting/month)
- 🌟🌟🌟🌟🌟 $2,000/month - Gold (10hrs consulting/month)

**Every dollar helps**:

- Keep tools maintained and updated
- Fund new tool development
- Provide support and documentation
- Make Dazzle better for everyone

### The Open-Source Problem

Like many open source projects, Dazzle faces the challenge that **most users don't have a good way to contribute back**. If everyone who uses these tools contributed just $5/month, we could easily:
- Build and release 10+ new Dazzle tools per year
- Provide individual support
- Create detailed tutorials and training
- Launch the full build environment system

**Be the change**: [Sponsor now](https://github.com/sponsors/djdarcy) and help make better tools for everyone.

---

## Roadmap

### Current Focus (Q4-Q1 2025-2026)
- ✅ Organize GitHub organizations
- 🚧 Migrate DazzleTools from personal repos
- 🚧 Publish all stable tools to PyPI
- 🚧 Launch DazzleProj.com website
- 🚧 Create beginner-friendly installation guides

### Near Term (Q2-Q4 2026)
- Cross-platform build environment (setenv.py)
- Video tutorials for common tasks
- Windows installer for non-technical users
- Expanded DazzleML tools
- Community bounty board (if funding goals met)

### Long Term (2027+)
- GUI versions of popular command-line tools
- Mobile companion apps
- Hosted/cloud options for some tools
- Training programs (and who knows maybe even certs similar to sendmail / Apache)
- Enterprise support packages

*Note: Ambitious roadmap depends heavily on community support and sponsorship. With funding, timelines accelerate significantly.*

---

## Community & Support

- **Documentation**: Individual project repositories
- **Questions**: GitHub Discussions in each project
- **Bug Reports**: GitHub Issues in relevant project
- **Feature Requests**: GitHub Discussions
- **Website**: [DazzleProj.com](https://dazzleproj.com) *(coming soon)*

---

## Frequently Asked Questions

**Q: What are the five Dazzle organizations?**
A: **DazzleProj** (build environment), **DazzleLib** (libraries), **DazzleTools** (utilities), **DazzleNodes** (ComfyUI), and **DazzleML** (AI tools). Think of it like the Linux project structure -- one umbrella coordinating specialized components.

**Q: Do I need to be technical to use Dazzle tools?**
A: Many tools are command-line based, but we're working on beginner-friendly guides and GUIs.

**Q: Is everything really free?**
A: Yes! Core tools are open source and free to use as you like. Some specialized tools have commercial licenses for businesses.

**Q: Can I use this at my company?**
A: Yes! Check individual tool licenses. Most are GPL3/MIT which allow commercial use.

**Q: How do I get support?**
A: File issues on GitHub. Sponsors get priority support and direct assistance.

**Q: Can I contribute without coding?**
A: Absolutely! Report bugs, suggest features, improve docs, sponsor development, or spread the word.

**Q: Why not just use [existing tool]?**
A: Many existing tools are platform-specific, expensive, or don't integrate well. Dazzle provides free, cross-platform alternatives that work together.

---

## Acknowledgments

Built with:
- Years of real-world system management experience
- Lessons learned from managing IT infrastructure, home networks, and development environments
- Feedback and needs from real users facing real problems
- Modern AI assistance for productivity gains
- The open source community's countless contributions

All code is original and independently developed.

---

## License

The Dazzle ecosystem uses multiple licenses:
- **DazzleLib**: MIT License (use anywhere)
- **DazzleTools**: Primarily GPL 3.0 (some commercial options)
- **DazzleNodes**: MIT License (ComfyUI compatible)
- **DazzleML**: GPL 3.0

See individual repositories for specific license files.

---

## Contact

- **GitHub**: [@djdarcy](https://github.com/djdarcy)
- **Issues**: Use repository-specific issue trackers
- **Sponsorship**: [GitHub Sponsors](https://github.com/sponsors/djdarcy)
- **Website**: [DazzleProj.com](https://dazzleproj.com) *(coming soon)*

---

**Better system management for everyone** 🛠️

*Because managing computers shouldn't be hard.*
