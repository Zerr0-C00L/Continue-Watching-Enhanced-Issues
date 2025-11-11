# Continue Watching Enhanced - Issues & Support

⚠️ **PROJECT ON PAUSE**

This is the **public issue tracker** for [Continue Watching Enhanced](https://continue-watching-enhanced.vercel.app), a Stremio addon project that is currently **paused indefinitely** due to technical limitations.

> **Note:** This repository is for bug reports, feature requests, and support only. The source code is maintained in a private repository.

## Why Paused?

Remote addons cannot access your local Stremio watch history (platform privacy/security limitation). The features this addon was designed to provide - keeping finished shows visible longer, adding rewatch counts, custom sorting - all require access to your viewing data that remote addons don't have.

**What was tried:**
- ✅ Built working local version (requires running server on your machine)
- ❌ Attempted remote catalog-based approach (no access to watch history)
- ❌ Explored meta handler enhancements (text/badges don't render)

**Current status:** The addon installs but does nothing. What you see in Continue Watching is Stremio's default behavior, not this addon.

## 🐛 Report a Bug

If you installed the addon and experienced issues, you can still [open a bug report](../../issues/new?template=bug_report.yml). However, please note the addon is currently non-functional.

## ✨ Request a Feature

Have an idea for how this could work within Stremio's API constraints? [Submit a feature request](../../issues/new?template=feature_request.yml) - creative solutions welcome!

## 💬 Ask a Question

Need clarification about the project status or technical details? [Ask a question](../../issues/new?template=question.yml)

## What Was Planned

- Keep series visible in Continue Watching longer (they normally rotate out)
- Add rewatch counts and badges for comfort shows
- Custom sorting based on viewing patterns and streaks
- Resume timestamps and progress indicators
- Re-add finished shows you've watched many times

**Note:** Basic Continue Watching functionality (showing finished episodes with next episode ready) is Stremio's default behavior - no addon needed for that.

## 🔮 Future

If Stremio's API evolves to allow remote addons to access watch data (with user permission), or if a workaround is discovered, development may resume. For now, the technical constraints make this impossible as a hosted addon.

**Interested in the local version?** The working code is in a private repo. If there's enough community interest, it may be open-sourced for those comfortable running local servers.

## 🔒 Privacy & Trust

**Why is the source code private?**  
The core addon code is kept private for now, but we're committed to transparency through this public issue tracker.

When functional, this addon would operate through Stremio's standard public APIs only. No personal data collection, no external tracking.

## 📞 Contact

- **Bug reports & features**: Open an issue in this repository
- **General discussion**: [r/Stremio on Reddit](https://www.reddit.com/r/Stremio)
- **Addon homepage**: https://continue-watching-enhanced.vercel.app

---

Thank you for your interest in Continue Watching Enhanced! 🎬
