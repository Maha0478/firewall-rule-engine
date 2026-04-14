# 🔥 Firewall Rule Engine

A powerful firewall rule analysis and generation engine built in **V (Vlang)**.  
Parse, analyze, optimize, and generate hardened firewall rulesets for **iptables** and **nftables**.

---

## ✨ What It Does

- 📥 **Parse** `iptables-save` and `nft list ruleset` formats into a unified rule model
- 🔍 **Detect** shadowed rules, contradictions, duplicates, and redundant entries
- ⚡ **Optimize** rulesets: port merging, rule reordering, missing rate limits, missing conntrack
- 🛡️ **Generate** hardened rulesets with default-deny, anti-spoofing, ICMP rate limiting, and connection tracking
- 🔄 **Export** rulesets between iptables and nftables formats
- 📊 **Diff** two rulesets to find what changed
- 🎨 **Colored terminal output** with severity-coded findings

---

## 📁 Project Structure

\`\`\`
src/
├── analyzer/   # Conflict detection & rule optimization
├── config/     # Configuration management
├── display/    # Colored terminal output
├── generator/  # Hardened ruleset generation
├── models/     # Unified rule data structures
└── parser/     # iptables & nftables parsers
\`\`\`

---

## 🚀 Installation

\`\`\`bash
./install.sh
\`\`\`

## ▶️ Usage

\`\`\`bash
v run .
\`\`\`

## 🧪 Tests

\`\`\`bash
v test .
\`\`\`

---

## 🛠️ Built With

- [V (Vlang)](https://vlang.io/) — Fast, safe, compiled language

---

## 📄 License
