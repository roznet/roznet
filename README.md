## Welcome to my GitHub

This github page contains my open source personal projects. You can follow their development on https://ro-z.net

### Fitness data deep dive

I am interested in fitness app and how to do analysis on your outdoor sports data. I maintain the open source iOS app [ConnectStats](https://github.com/roznet/connectstats) that contains an [iPhone app](https://ro-z.net/blog/connectstats/documentation/) that has been around and in [the store](https://itunes.apple.com/app/apple-store/id581697248?mt=8) since 2011/2012. You can also find an accompanying [server](https://github.com/roznet/connectstats_server) to handle Garmin data using [their official API](https://ro-z.net/blog/connectstats/never-ending-service-and-server-saga/). As a bonus, the app [FitFileExplorer](https://github.com/roznet/connectstats) allows you to open and see Fit Files on your mac.

In the process of developping ConnectStats I required a fast Fit file library compatible with swift, so a [adapted the SDK](https://github.com/roznet/FitFileParser)

### Flying apps and tools

I am a private pilot and most of my recent projects are aviation-related.

**[euro_aip](https://github.com/roznet/rzflight)** (rzflight) - Python and Swift library for European AIP data: airport database (5000+ airports), procedure queries, NOTAM/briefing parsing, and a web map at maps.flyfun.aero. Published as `pip install euro-aip`.

**[FlyFunApps](https://github.com/roznet/flyfun-apps)** - Full-stack aviation information system: airport explorer with AI chatbot, interactive maps, GA friendliness scoring, ForeFlight integration. React/TypeScript frontend, FastAPI backend, SwiftUI iOS app. Features an MCP server for LLM integration.

**[FlyFunWeather](https://github.com/roznet/flyfun-weather)** - Medium-range aviation weather assessment for cross-country GA flights in Europe. Multi-model forecasts (GFS, ECMWF, ICON, etc.), ~40 derived aviation metrics, interactive cross-section visualization, skew-T soundings, and route advisories with hazard grading.

I also maintain a few smaller flying projects: [mental-crosswind](https://github.com/roznet/mental-crosswind) to practice crosswind mental math, [flightlogstats](https://github.com/roznet/flightlogstats) for Garmin G1000 log analysis, and [flyfunboarding](https://github.com/roznet/flyfunboarding) for issuing fun boarding passes to friends.

### Tools to make my life easier

**[mcp-library-docs](https://github.com/roznet/mcp-library-docs)** - An MCP server that gives Claude access to design documentation across multiple code libraries. Enables Claude sessions working in one repo to discover and understand utilities from other repos, preventing reimplementation and keeping architectural decisions accessible. Zero-config discovery from any project with a `designs/` directory.

I also published a [few utilities](https://github.com/roznet/quickutils) to keep my linux and macOS machines in sync, debug bonjour, and find iOS Simulator files from the terminal.

### Project for learning and fun

[RemoteStash](https://github.com/roznet/remotestash) is a small tool built to substitute for AirDrop when you want to share file or text between Linux and an iPhone. It was build to learn about network discovery and exchange of information on the fly between phone and computer but it turned [out pretty useful](https://ro-z.net/blog/ios-development/how-to-airdrop-to-linux-part-1/)...




<!--
**roznet/roznet** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
