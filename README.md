<a href="https://wallpad.run"><img src="https://wallpad.run/assets/brand/banner.png" width="100%" alt="WALL. Every stream gets a coin. The chat cuts the clips. wallpad.run"></a>

<div align="center">
<a href="https://wallpad.run"><img src="https://img.shields.io/badge/wallpad.run-the%20wall-53FC18?style=for-the-badge&labelColor=07080A" alt="wallpad.run"></a>
<a href="https://x.com/justwallpad"><img src="https://img.shields.io/badge/x-%40justwallpad-07080A?style=for-the-badge&logo=x&logoColor=53FC18&labelColor=07080A" alt="x"></a>
<a href="https://wallpad.run/launch.html"><img src="https://img.shields.io/badge/launch-a%20coin-7C3AED?style=for-the-badge&logo=solana&logoColor=F3F5F1&labelColor=07080A" alt="launch a coin"></a>
<a href="https://github.com/wallpadSOL/wall"><img src="https://img.shields.io/badge/agent-source-07080A?style=for-the-badge&logo=github&logoColor=53FC18&labelColor=07080A" alt="agent source"></a>
<img src="https://img.shields.io/github/followers/wallpadSOL?style=for-the-badge&logo=github&logoColor=53FC18&color=07080A&labelColor=07080A&label=followers" alt="followers">
<a href="https://github.com/wallpadSOL/wall/stargazers"><img src="https://img.shields.io/github/stars/wallpadSOL/wall?style=for-the-badge&logo=github&logoColor=53FC18&color=07080A&labelColor=07080A&label=stars" alt="stars"></a>
</div>

<br>

### 🧱 What WALL is

```toml
[wall]
is      = "a launchpad for live streams on Solana"
coin    = "one per Kick or Twitch stream, launched by whoever gets there first"
line    = "the room runs 3x its own last minute"
cut     = "a 30 second clip, the moment the line is crossed, verdict written in public"
fees    = { burn = "40%", launchers = "40%", platform = "20%" }   # every hour, on chain
never   = ["posts in chat", "trades", "touches your keys"]
site    = "https://wallpad.run"
```

### 🧰 Stack

<p align="center">
<img src="https://img.shields.io/badge/Python-07080A?style=for-the-badge&logo=python&logoColor=53FC18" alt="Python">
<img src="https://img.shields.io/badge/Solana-07080A?style=for-the-badge&logo=solana&logoColor=53FC18" alt="Solana">
<img src="https://img.shields.io/badge/pump.fun-07080A?style=for-the-badge&logoColor=53FC18" alt="pump.fun">
<img src="https://img.shields.io/badge/FFmpeg-07080A?style=for-the-badge&logo=ffmpeg&logoColor=53FC18" alt="FFmpeg">
<img src="https://img.shields.io/badge/Caddy-07080A?style=for-the-badge&logo=caddy&logoColor=53FC18" alt="Caddy">
</p>
<p align="center">
<img src="https://img.shields.io/badge/Kick-07080A?style=for-the-badge&logo=kick&logoColor=53FC18" alt="Kick">
<img src="https://img.shields.io/badge/Twitch-07080A?style=for-the-badge&logo=twitch&logoColor=A970FF" alt="Twitch">
<img src="https://img.shields.io/badge/Netlify-07080A?style=for-the-badge&logo=netlify&logoColor=53FC18" alt="Netlify">
<img src="https://img.shields.io/badge/Dexscreener-07080A?style=for-the-badge&logoColor=53FC18" alt="Dexscreener">
<img src="https://img.shields.io/badge/Claude%20Code-07080A?style=for-the-badge&logo=claude&logoColor=53FC18" alt="Claude Code">
</p>

### ⚙️ How a stream becomes a coin

| Step | What happens |
|---|---|
| 👀 **Watch** | paste a live Kick or Twitch link. The agent joins that chat and counts messages per second, nothing else |
| 📈 **The line** | every room is measured against its own last minute. 3x is the line, for every stream, always |
| ✂️ **Cut** | the moment the line is crossed the agent cuts a 30 s clip from the buffer and writes the verdict in public |
| 🪙 **Launch** | one coin per stream on pump.fun, created from one hot wallet, so the launcher never signs with a key they don't own |
| 💸 **Fees** | every hour: 40% buys and burns $WALL, 40% goes back to launchers by volume, 20% runs the platform |

> One rule for every stream. The agent never posts in a chat and never trades. If a number is on the wall, the json it came from is public.

### 🏹 Now shipping

<a href="https://github.com/wallpadSOL/wall"><img src="https://wallpad.run/assets/og.jpg" width="100%" alt="wall, the agent and the site"></a>

<p align="center"><a href="https://github.com/wallpadSOL/wall"><img src="https://img.shields.io/badge/github.com%2FwallpadSOL%2Fwall-open%20the%20repo-53FC18?style=for-the-badge&logo=github&logoColor=07080A&labelColor=07080A" alt="wall repo"></a></p>

<div align="center">
<img src="https://img.shields.io/badge/the%20line-3x%20the%20last%20minute-53FC18?style=for-the-badge&labelColor=07080A" alt="the line">
<img src="https://img.shields.io/badge/the%20cut-30%20s%2C%20from%20the%20buffer-53FC18?style=for-the-badge&labelColor=07080A" alt="the cut">
<img src="https://img.shields.io/badge/fees-40%20%2F%2040%20%2F%2020%2C%20hourly-53FC18?style=for-the-badge&labelColor=07080A" alt="fees">
<img src="https://img.shields.io/badge/chats-Kick%20%2B%20Twitch-53FC18?style=for-the-badge&labelColor=07080A" alt="chats">
<img src="https://img.shields.io/badge/the%20agent-never%20posts%2C%20never%20trades-7C3AED?style=for-the-badge&labelColor=07080A" alt="never">
</div>

<p align="center"><sub>the rules as the agent runs them. the public json: <a href="https://api.wallpad.run/state.json">state</a> · <a href="https://api.wallpad.run/spikes.json">spikes</a> · <a href="https://api.wallpad.run/clips.json">clips</a> · <a href="https://api.wallpad.run/coins.json">coins</a> · <a href="https://api.wallpad.run/fees.json">fees</a></sub></p>

<br>

<div align="center">
<a href="https://wallpad.run"><img src="https://img.shields.io/badge/the%20wall-07080A?style=for-the-badge&labelColor=07080A&color=07080A" alt="the wall"></a>
<a href="https://wallpad.run/cuts.html"><img src="https://img.shields.io/badge/cuts-07080A?style=for-the-badge&labelColor=07080A" alt="cuts"></a>
<a href="https://wallpad.run/fees.html"><img src="https://img.shields.io/badge/fees-07080A?style=for-the-badge&labelColor=07080A" alt="fees"></a>
<a href="https://wallpad.run/launch.html"><img src="https://img.shields.io/badge/launch%20a%20coin-53FC18?style=for-the-badge&labelColor=07080A&color=53FC18" alt="launch a coin"></a>
</div>

<p align="center"><sub>built in public · <a href="https://wallpad.run">wallpad.run</a> · <a href="https://x.com/justwallpad">@justwallpad</a></sub></p>
