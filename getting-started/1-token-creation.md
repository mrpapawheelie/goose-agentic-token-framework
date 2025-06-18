# Token Creation

## Tasks
- [ ] Export your contract from basescan and place it in the `contracts/` folder.
- [ ] Set up your token parameters (name, symbol, supply, etc.).
- [ ] Add your token icon to `branding/icon.png` (must be 1024x1024 PNG).

## Walkthrough Video
<!-- Embed or link your walkthrough video here -->

[//]: # (Replace this with a YouTube or Loom link when ready)

---

# Agent Token Name Generator

**Formula:**  
**[Prefix Word] + [Descriptor or Action Word] = Agent Name**  
→ Suggested **Ticker** (4–6 chars, unique, easy to type)

> **Note on Naming:**  
Alliterated token names follow **phonetic alliteration**, meaning they repeat the same sound, not just the same starting letter. For example, **Phantom Flux** works because "Ph" and "F" create the same "fuh" sound. This gives you more creative freedom while keeping the names catchy and memorable.

---

### 🧠 Smart / Strategic Agents

| Name              | Ticker | Vibe                                 |
|-------------------|--------|--------------------------------------|
| Silent Signal     | SIGX   | Data-driven stealth operator         |
| Alpha Algo        | ALGOX  | Precision and calculation            |
| Echo Edge         | ECED   | Feedback loop and market edge        |
| Meta Machina      | METAQ  | Predictive tactical agent            |
| Logic Link        | LOGL   | Connector of info flows              |

---

### ⚔️ Aggressive / Speed Bots

| Name              | Ticker | Vibe                                 |
|-------------------|--------|--------------------------------------|
| Blitz Pulse       | BZPL   | HFT-style strike bot                 |
| Feral Flux        | FRFX   | Wild, reactive price action          |
| Phantom Force     | PHFX   | Appears suddenly, dominates          |
| Signal Storm      | SGST   | Market chaos and trend chasing       |
| Kinetic Kore      | KNKR   | Constant energy, centered force      |

---

### 🕶️ Covert / Minimalist Bots

| Name              | Ticker | Vibe                                 |
|-------------------|--------|--------------------------------------|
| Covert Circuit    | CVRC   | Secret, high-function logic loop     |
| Ghost Grid        | GHGD   | Operates silently within data streams|
| Dark Data         | DRKD   | Hidden alpha in deep market signals  |
| Stealth Script    | STSC   | Low noise, high alpha                |
| Null Node         | NULLX  | Minimalist logic core                |

---

### ⚡ Mythic / Symbolic Edge

| Name              | Ticker | Vibe                                 |
|-------------------|--------|--------------------------------------|
| Athena Algo       | ATHA   | Wisdom + algorithmic execution       |
| Macro Mode        | MCRD   | High-level strategy engine           |
| Odin Order        | ODNR   | Visionary and structured force       |
| Zero Zenith       | ZZEN   | From zero to the highest peak        |
| Vanta Vector      | VANTX  | Obsidian black energy burst          |

---

### 🎮 Bonus: Game-Like Signal Bots (Fake, But Fire)

| Name              | Ticker | Vibe                                 |
|-------------------|--------|--------------------------------------|
| Arbee             | ARBX   | Casual signal bot with charm         |
| Zynthi            | ZYNX   | Flashy synthetic pulse reader        |
| Zynthy            | ZYTY   | Alternate branding for fast reflexes |
| Dark Degen        | DGEN   | Chaotic yet calculated               |
| Alpha Atom        | ALAT   | Core strength with smart moves       |

---

# Creating the Perfect Token

Follow these guidelines to create a memorable, discoverable, and professional token. You can use the sample AI prompts below to help brainstorm ideas.

## 1. Ticker (Symbol)
- **Requirements:**
  - Unique (not already used by another token)
  - Easy to spell
  - No more than 6 characters (so it can be cashtagged, e.g., $TOKEN)
  - **Do not use 'Goose' or 'Agent' in your ticker.**
- **Reasoning:**
  - Common or long tickers are hard to find and use on social platforms.
- **Good Examples:**
  - ZYNTH, BLAZE
- **Bad Examples:**
  - TOKEN (too generic), AGENTIC (too long), ETH (already taken), CRYPTO123 (too long, not memorable), GOOSE, AGENT
- **Sample AI Prompt:**
  > Suggest 10 unique, easy-to-spell, 4-6 letter token tickers for an AI agent project. Avoid common or existing crypto tickers, and do not use 'Goose' or 'Agent'.

## 2. Name
- **Requirements:**
  - Capital case, one word or max two words
  - Unique but easy to spell
  - If two words, use rhythmic alliteration (e.g., "MetaMind")
  - **Do not use 'Goose' or 'Agent' in your token name.**
- **Reasoning:**
  - Alliteration and rhythm make names more memorable. (e.g., "MetaMind" is alliterative, but try to be more unique)
- **Good Examples:**
  - BlazeBot, ZynthAI, BlazeByte, NovaNode
- **Bad Examples:**
  - GooseAgent, agentic token (not capitalized, two generic words), Crypto Token (too generic), The Best Agent (too long, not unique), MetaMind (too common)
- **Sample AI Prompt:**
  > Suggest 10 unique, catchy, capitalized token names (one or two words, using alliteration if two words) for an AI agent project. Do not use 'Goose' or 'Agent'.

## 3. Description
- **Requirements:**
  - Super short (max 66 characters)
  - Unique, clear, and states exactly what your token is for
- **Good Examples:**
  - "AI-powered agent for on-chain automation."
  - "A minimal, fast, and secure token for Web3 agents."
- **Bad Examples:**
  - "This is a token." (too vague)
  - "The best token for everything you need in crypto and more!" (too long, not specific)
- **Sample AI Prompt:**
  > Write a unique, clear, and concise (max 66 characters) description for a token that powers an AI agent for blockchain automation.

## 4. Icon
- **Requirements:**
  - Unique, minimalistic, and relevant to the name
  - Use simple lines, high contrast, and minimal detail
  - Should be recognizable at 32px size
- **Reasoning:**
  - Icons are often displayed very small; clarity and simplicity are key.
- **Tips:**
  - Avoid text or complex backgrounds
  - Use bold shapes and clear silhouettes
  - Make sure the icon stands out against both light and dark backgrounds
- **Sample AI Prompt:**
  > Describe a minimalistic, unique icon concept for a token named "BlazeBot" that would be recognizable at 32px and relevant to the name.

You can upload examples of good and bad icons for reference.

---

# Importing Contracts

Follow these steps to download and add your contract source code:

1. **Install the MetaSuites Extension**  
   Go to the [MetaSuites - Builders' Swiss Army Knife Chrome Extension](https://chromewebstore.google.com/detail/metasuites-builders-swiss/fkhgpeojcbhimodmppkbbliepkpcgcoo) and click "Add to Chrome".

2. **Find Your Token on Basescan**  
   Go to [basescan.org](https://basescan.org/) and search for your token address, or click the link icon next to your token address if you're already on the page.

3. **Download the Contract Source**  
   Click the **Contract** tab.  
   Click the **Download ZIP** button (provided by the MetaSuites extension).

4. **Unzip the Downloaded File**  
   Extract the ZIP file on your computer.

5. **Add to Your Repo**  
   Drag and drop the extracted contract files into the `contracts/` directory of your project repository.

6. **Commit and Push**  
   Commit the changes and push to your fork or branch, or upload via the GitHub website.

---

**Why use MetaSuites?**

MetaSuites makes it easy to download verified contract source code and ABIs directly from block explorers like Basescan, Etherscan, and others, streamlining the process for your cohorts.  
[Learn more about MetaSuites on the Chrome Web Store](https://chromewebstore.google.com/detail/metasuites-builders-swiss/fkhgpeojcbhimodmppkbbliepkpcgcoo). 