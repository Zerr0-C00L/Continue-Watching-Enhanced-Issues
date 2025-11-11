# Continue Watching Enhanced - Issues & Support

This is the **public issue tracker** for [Continue Watching Enhanced](https://continue-watching-enhanced.vercel.app), a Stremio addon that enhances the Continue Watching row with rewatch counts, resume timestamps, and progress indicators.

> **Note:** This repository is for bug reports, feature requests, and support only. The source code is maintained in a private repository.

## ⚠️ IMPORTANT: Local Installation Required

**This addon does NOT work when installed from the hosted URL.** Remote addons cannot access your local Stremio watch data due to platform limitations.

**You must run the addon locally** on the same machine as Stremio for it to function. See installation instructions on the [addon homepage](https://continue-watching-enhanced.vercel.app).

## 🐛 Report a Bug

Found a bug? [Open a bug report](../../issues/new?template=bug_report.yml) with:
- Your platform (Web, Desktop, Android TV, etc.)
- Stremio version
- **Confirmation that you're running the addon locally** (not from hosted URL)
- Clear steps to reproduce
- Expected vs. actual behavior

## ✨ Request a Feature

Have an idea? [Submit a feature request](../../issues/new?template=feature_request.yml) describing:
- The problem you're trying to solve
- Your proposed solution
- Any alternatives you've considered

## 💬 Ask a Question

Need help? [Ask a question](../../issues/new?template=question.yml) and we'll do our best to assist.

## 🔒 Privacy & Trust

**Why is the source code private?**  
The core addon code is kept private for now, but we're committed to transparency:

- All data processing happens **locally** within your Stremio app
- **No external servers** store or track your viewing data
- The addon only **reads** your Stremio watched/library data—never modifies it
- Full privacy details are available on the [addon homepage](https://continue-watching-enhanced.vercel.app)

We welcome scrutiny and will answer any questions about how the addon works.

## 📦 Installation

**The addon requires local installation.** Visit **https://continue-watching-enhanced.vercel.app** for complete setup instructions.

**Quick steps:**
1. Clone/download the addon code
2. Run `npm install` then `npx stremio-addon-runner addon-local.js`
3. In Stremio → Addons → Install from URL: `http://127.0.0.1:7000/manifest.json`
4. Watch content for 30+ seconds to see enhancements

**The hosted manifest URL does not work** because remote addons cannot access your local watch data.

## 🌟 Features

- **Rewatch counts**: Shows how many times you've watched something (e.g., "Billy the Kid (3×)")
- **Resume timestamps**: "Resume at 23:45" or "Almost done — 2 min left"
- **Badge icons**: 🔥 flame at 5+ rewatches, 👑 crown at 10+
- **Zero extra catalogs**: Enhances the existing Continue Watching row without clutter

## ⚠️ Beta Status

This addon is currently in beta. If you encounter issues, please report them here. Not all bugs may be fixed immediately—we appreciate your patience and feedback!

## 📞 Contact

- **Bug reports & features**: Open an issue in this repository
- **General discussion**: [r/Stremio on Reddit](https://www.reddit.com/r/Stremio)
- **Addon homepage**: https://continue-watching-enhanced.vercel.app

---

Thank you for using Continue Watching Enhanced! 🎬
