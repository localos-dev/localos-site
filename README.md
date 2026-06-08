# localos-site

Source code for the localos.xyz website. Covers the landing page, feature pages, install guide, model catalog, and payment information.

Website: https://localos.xyz
Docs: https://localos.xyz/docs
X: https://x.com/localos_xyz

---

## What this repo contains

The marketing and informational website for LocalOS. This is separate from the application itself.

Landing page with product overview, feature highlights, and model catalog. Install guide written for end users with no technical background. Models page with free and paid tier information, wallet connection, and USDC payment flow on Base.

All content is in English with no symbols, no arrows, no emoji.

---

## Pages

| Page | Path | Description |
|---|---|---|
| LandingPage | / | Product overview, hero, features, how it works, model catalog, CTA |
| ModelsPage | /models | Full model catalog, free and paid tiers, wallet connect, payment modal |
| FeaturesPage | /features | Feature overview: chat, code editor, web builder, knowledge base |
| InstallPage | /install | Step-by-step guide for non-technical users |
| AboutPage | /about | Project background and mission |
| ChangelogPage | /changelog | Release history |
| ChatFeaturePage | /features/chat | Chat feature detail page |
| CodeEditorPage | /features/code-editor | Code editor feature detail page |
| BuildFeaturePage | /features/build | Web builder feature detail page |
| KnowledgeBasePage | /features/knowledge-base | Knowledge base feature detail page |
| ProjectsFeaturePage | /features/projects | Projects feature detail page |
| ContextMemoryPage | /features/context-memory | Context and memory feature detail page |
| WebBuilderPage | /features/web-builder | Web builder feature detail page |
| LlamaModelsPage | /models/llama | Llama model family detail |
| OtherModelsPage | /models/other | Other model families detail |
| CommunityPage | /community | Community links and contribution info |
| ContactPage | /contact | Contact information |
| PrivacyPage | /privacy | Privacy policy |
| TermsPage | /terms | Terms of service |
| not-found | * | 404 not found page |

---

## Model access

Models under 2 GB are free. No wallet required.

Larger models require a one-time USDC payment on Base. The user connects a wallet (MetaMask, Coinbase Wallet, or any injected browser wallet), sends USDC to a backend-generated address, and the backend relay confirms and grants access. Payment is per wallet per model. No subscription.

Pricing tiers: free under 2 GB, 15 USDC for 2 to 3 GB, 20 USDC for 3 to 4 GB, 25 USDC for 4 GB and above.

---

## Running locally

Requirements: Node.js 24, pnpm 9 or later.

Install dependencies:

```
pnpm install
```

Start the dev server:

```
pnpm run dev
```

Open the browser at the URL shown in the terminal output.

---

## Content rules

All text on this site follows the LocalOS content rules:

No symbols of any kind. No emoji, no arrows, no checkmarks, no em dashes, no en dashes. Plain English words and punctuation only.

All text in English.

User-first. The primary reader is a non-technical user who wants to run AI locally. Developer information appears after the user content, never before.

No mention of cloud, accounts, or API keys as requirements. LocalOS needs none of these for basic use. A wallet is only needed for paid models.

Never use the internal name of the LLM runtime in user-facing text. Use "LLM runtime" or "language model" instead.

---

## Links

Main app: https://github.com/localos-dev/localos
Docs: https://github.com/localos-dev/localos-docs
Model catalog: https://github.com/localos-dev/localos-models
Smart contract: https://github.com/localos-dev/localos-contracts
X: https://x.com/localos_xyz
