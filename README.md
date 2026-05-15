# PRJCT0 web mockup

> Terminal-style fair-launch landing page for [PRJCT0](https://github.com/Khimsaja/prjct0-contract).

```
guest@prjct0:~/mint $ ssh prjct0.xyz
[ ok ] connected — type help
```

Standalone HTML file. No build step, no framework. JetBrains Mono + VT323 + vanilla JS.

## Features

- 🟢 Phosphor green CRT terminal vibe inside a macOS-style window
- ⌨️ Boot sequence typewriter on first load (login as: prompt)
- 💻 Interactive shell — `help`, `mint`, `connect`, `status`, `whitepaper`, etc.
- 🎨 Theme switcher: green / amber / cyan / magenta
- 🔊 Optional WebAudio keystroke + chime SFX
- 🥚 Easter eggs: `cowsay`, `sl`, `vim`, `hack the planet`, `fortune`, `whoami`, ...
- 📱 Mobile-friendly layout

## Run locally

```bash
python3 -m http.server 8787
# then open http://localhost:8787/
```

Or just open `index.html` in a browser.

## Live

Domain: `kleinnn.my.id` (coming soon, awaiting DNS propagation)

## Status

This is a **mockup**. It does NOT yet talk to the deployed contract — wallet connect is currently simulated. Real wagmi+viem integration lands once the contract is on Base mainnet.

## License

MIT
