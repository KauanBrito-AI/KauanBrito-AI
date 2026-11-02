## Hi, I'm Kauan.

I build working AI systems, and the content that gets people to use them.

Content creator and AI-native builder from Brazil, moving to Dublin in December 2026. As a one-person studio I grew a consumer-tech channel to **107,000+ followers in 18 months**, then built everything behind it by directing AI coding agents (Claude Code, Codex): the website, two paid products, a six-language web app and the automation that runs them. Before that, I worked in political and public-sector marketing (2019–2025).

**How I work:** I make the product, architecture and quality calls. The agents write most of the code. I review it running in a real browser, and I build checks that run on their own, because "looks fine to me" is not a quality gate.

---

### Featured code

| Repository | What it shows |
|---|---|
| [**research-to-article-pipeline**](https://github.com/KauanBrito-AI/research-to-article-pipeline) | LLM pipeline with structured output and two quality gates. The story starts with the AI robot I switched off before launch. |
| [**photo-privacy-cleaner**](https://github.com/KauanBrito-AI/photo-privacy-cleaner) | Removes GPS, camera data and AI provenance stamps from photos byte by byte: zero quality loss, nothing uploaded. Two real bugs and how they were fixed. |
| [**search-console-report**](https://github.com/KauanBrito-AI/search-console-report) | Google and Bing APIs with no SDK, turned into a weekly list of what to fix. Found a sitemap Google had ignored for nine months. |

---

### Everything else I've built

Most of this runs in production for my own products, so the code stays private. Ask me about any of it.

**AI and automation**

| What | How | Status |
|---|---|---|
| Content production agents | Six custom Claude skills that research, script, design, review, plan the week and write the newsletter for the channel | In daily use |
| AI tools directory | 710 tools published to WordPress through its REST API in batches; a triage step cut 582 raw mentions to the ones that were verified and still online | Live |
| Image quality gate | Automated check on every carousel screenshot before publishing; it rejected 11 images where a visual review had caught 2 | In use |
| Social DM funnel pages | The link sent after "comment X and I'll send it" points to a page generated and published by a script through the WordPress API, with nothing to deploy | Live |
| Brand-partnership CRM | Proposals tracked in Notion through its API, updated as replies go out | In use |
| News-rewriting robot | Make.com + LLM + WordPress, three posts a day. Built, then switched off before launch: it matched Google's scaled-content-abuse pattern | Retired on purpose |

**Web products**

| What | How | Status |
|---|---|---|
| [Wavecabin](https://wavecabin.com) | Six-language web app for musicians: machine-learning stem separation on the user's device (ONNX Runtime Web, WebGPU/WASM), a music visualiser exporting 4K at 60 fps, beat- and drop-detection for animated covers, accounts, local-currency subscriptions, signed licences, privacy-first analytics, all on Cloudflare Pages, Functions and D1 | Live since Oct 2026 |
| Prompt studio (paid) | Members-only web app: 700+ prompts, 12 guided projects, 16 motion effects with live demos, server-side scheduled releases, an in-product rating system with a minimum-vote floor | Live, 12 sales on launch day |
| Paid listings for the directory | Click tracking with bot filtering and rate limits, private monthly report links, a daily job that e-mails each brand its report, PayPal subscriptions, in Portuguese and English | Live |
| Nine in-browser file tools | Merge, split, rotate and convert PDFs; compress, resize and convert images; strip metadata. Files never leave the device | Live |
| Video-editing engine | An LLM writes the edit as a JSON script; the browser renders the video | In development |

**Video made with code**

| What | How |
|---|---|
| Product explainer | A 36-second explainer animated on canvas and encoded to MP4 in the browser with WebCodecs, in two resolutions |
| Promo videos in three languages | Narration-driven timeline, synthetic voice-over, sound effects synthesised in code, vertical and horizontal cuts from the same source |
| Automatic previews | Finds the strongest 15 seconds of a song by audio energy and bass, starting at the biggest energy rise, and cuts the preview there |

**Marketing technology and site operations**

| What | How |
|---|---|
| Ads tracking | Meta Pixel and Conversions API behind cookie consent; campaign tags preserved through to checkout |
| Search visibility | Weekly Search Console and Bing reports, IndexNow on every deploy, an `llms.txt` for AI crawlers; cited 51 times in Bing's AI answers in six months |
| Site audit | Found the largest paint on mobile was the cookie banner, and that an antivirus was injecting scripts into the browser and skewing speed tests, so its scripts are now blocked during measurement; Cloudflare firewall rules for common attack paths |

---

### Elsewhere

[caminhotec.com.br](https://caminhotec.com.br) · [Instagram @caminhotec](https://www.instagram.com/caminhotec/) · [wavecabin.com](https://wavecabin.com) · caminhotec@gmail.com
