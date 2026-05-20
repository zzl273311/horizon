---
layout: default
title: "Horizon Summary: 2026-05-20 (EN)"
date: 2026-05-20
lang: en
---

> From 28 items, 12 important content pieces were selected

---

1. [Google Announces Gemini 3.5 Flash with Higher Pricing](#item-1) ⭐️ 9.0/10
2. [Alibaba Releases Qwen3.7-Max, a New Proprietary Frontier AI Model](#item-2) ⭐️ 8.0/10
3. [Saying Goodbye to Asm.js](#item-3) ⭐️ 8.0/10
4. [Meta Blocks Human Rights Accounts in Saudi Arabia, UAE](#item-4) ⭐️ 8.0/10
5. [Blog Post Lists Surprising C Undefined Behaviors](#item-5) ⭐️ 8.0/10
6. [EU launches Wero, sovereign payment alternative to Visa/Mastercard](#item-6) ⭐️ 8.0/10
7. [uv 0.11.15 released with security fixes and enhancements](#item-7) ⭐️ 7.0/10
8. [Google fights manipulation of AI search results](#item-8) ⭐️ 7.0/10
9. [Curated Index of Archived FiveThirtyEight Articles](#item-9) ⭐️ 7.0/10
10. [Japan's mass allergies traced to 1950s reforestation project](#item-10) ⭐️ 6.0/10
11. [Simon Willison Analyzes Gemini Spark and Antigravity at Google I/O](#item-11) ⭐️ 6.0/10
12. [Last 6 months of LLMs in a 5-minute talk](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Google Announces Gemini 3.5 Flash with Higher Pricing](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-5/) ⭐️ 9.0/10

Google has announced Gemini 3.5 Flash, a new multimodal language model, with a 3x price increase compared to its predecessor Gemini 3.0 Flash preview. This marks a significant shift in pricing strategy for the Flash series, raising questions about cost efficiency for developers and the model's positioning against competitors. Community members have noted that Gemini 3.5 Flash costs $1.50 per million input tokens and $9.00 per million output tokens, while earlier Flash models were much cheaper. Additionally, the model demonstrates efficient token usage for complex tasks like generating animated SVGs.

hackernews · spectraldrift · May 19, 17:43 · [Discussion](https://news.ycombinator.com/item?id=48196570)

**Background**: Gemini Flash is a series of lightweight, fast models from Google DeepMind designed for high throughput and low latency. The Flash series initially offered a cost-effective alternative to the larger Pro models, but Gemini 3.5 Flash now approaches Pro-level pricing while maintaining Flash speeds.

<details><summary>References</summary>
<ul>
<li><a href="https://deepmind.google/models/gemini/flash/">Gemini 3 . 5 Flash — Google DeepMind</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/models/gemini-3.5-flash">Gemini 3 . 5 Flash | Gemini API | Google AI for Developers</a></li>
<li><a href="https://en.wikipedia.org/wiki/Gemini_(language_model)">Gemini (language model) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community reaction is mixed: some users express concern over the 3x price hike and question the value proposition, while others highlight the model's technical strengths, such as efficient token usage and parameter inference from TPU specs. There is also discussion about the early 2025 knowledge cutoff requiring web search.

**Tags**: `#AI`, `#Google`, `#Gemini`, `#LLM`, `#pricing`

---

<a id="item-2"></a>
## [Alibaba Releases Qwen3.7-Max, a New Proprietary Frontier AI Model](https://qwen.ai/blog?id=qwen3.7) ⭐️ 8.0/10

Alibaba has announced Qwen3.7-Max, a new proprietary frontier AI model that achieves state-of-the-art performance in benchmarks like non-hallucination rate, surpassing competitors such as Opus 4.7, Gemini 3.1 Pro, and GPT5.5. This release underscores the rapid advancement of Chinese AI companies in the frontier model space, while sparking community debate about the openness of such models and the availability of affordable hosting options for developers worldwide. Qwen3.7-Max is the flagship text-only model with a higher capability ceiling, while Qwen3.7 Plus handles multimodal inputs. The model is proprietary, raising questions about whether an open-source version will follow, as with previous Qwen releases.

hackernews · kevinsimper · May 20, 10:35 · [Discussion](https://news.ycombinator.com/item?id=48205626)

**Background**: Frontier AI models are the most advanced machine learning models, typically trained on vast datasets and requiring massive computational resources. Many leading models, such as GPT-4 and Claude, are proprietary and accessible only via cloud APIs. Alibaba's Qwen series has historically offered both proprietary and open-source versions, with the open-source variants being popular for local deployment.

<details><summary>References</summary>
<ul>
<li><a href="https://www.buildfastwithai.com/blogs/qwen3-7-max-preview-alibaba-2026">Qwen3.7 Max Preview: Arena Ranks, Features & What's Next</a></li>
<li><a href="https://artificialanalysis.ai/models/qwen3-7-max">Qwen3.7 Max - Intelligence, Performance & Price Analysis</a></li>
<li><a href="https://en.wikipedia.org/wiki/Frontier_model">Frontier model</a></li>

</ul>
</details>

**Discussion**: Community members expressed excitement about the model's performance, with one user calling it state-of-the-art. Others raised concerns about hosting availability—particularly for users outside China—and whether an open-source release would follow. Some praised the value of open-source alternatives like Qwen3.6 for smaller tasks.

**Tags**: `#AI`, `#Qwen`, `#language models`, `#open source`, `#frontier models`

---

<a id="item-3"></a>
## [Saying Goodbye to Asm.js](https://spidermonkey.dev/blog/2026/05/20/saying-goodbye-to-asmjs.html) ⭐️ 8.0/10

Mozilla's SpiderMonkey team announced that asm.js support will be removed from the engine, officially sunsetting the technology. Asm.js was a pioneering technology that enabled near-native performance in browsers and paved the way for WebAssembly; its end marks a full transition to WebAssembly as the standard for high-performance web applications. Asm.js is a strict subset of JavaScript that allowed code from languages like C and C++ to run efficiently in the browser; SpiderMonkey will no longer apply special optimizations for asm.js code.

hackernews · eqrion · May 20, 12:01 · [Discussion](https://news.ycombinator.com/item?id=48206340)

**Background**: Asm.js was introduced by Mozilla in 2013 as a way to run C/C++ code in the browser at near-native speed by restricting JavaScript to a subset that engines could optimize aggressively. It was a key precursor to WebAssembly, which became a standardized binary format for the web. SpiderMonkey is Mozilla's JavaScript and WebAssembly engine used in Firefox. The removal of asm.js support reflects the industry's complete shift to WebAssembly.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Asm.js">asm.js - Wikipedia</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Games/Tools/asm.js">asm.js - Game development - MDN Web Docs</a></li>
<li><a href="https://spidermonkey.dev/">Home | SpiderMonkey JavaScript/WebAssembly Engine</a></li>

</ul>
</details>

**Discussion**: Community comments reflect a mix of nostalgia and appreciation for asm.js's role in enabling early demos like Unreal Engine in the browser and real-world products such as Figma, while some users note WebAssembly's limitations regarding direct Web API access without shims.

**Tags**: `#asm.js`, `#WebAssembly`, `#SpiderMonkey`, `#browser technology`, `#JavaScript`

---

<a id="item-4"></a>
## [Meta Blocks Human Rights Accounts in Saudi Arabia, UAE](https://www.alqst.org/ar/posts/1190) ⭐️ 8.0/10

Meta has restricted human rights accounts from reaching audiences in Saudi Arabia and the United Arab Emirates, effectively censoring content critical of these governments. This action undermines free speech and highlights the tension between corporate compliance with authoritarian regimes and the protection of human rights. It sets a concerning precedent for how tech giants manage geopolitical pressures in sensitive regions. The specific accounts affected were not disclosed, but the move blocks content from users in Saudi Arabia and the UAE, where local laws often require platforms to suppress dissent. Meta likely acted to avoid being banned or penalized in these countries.

hackernews · giuliomagnifico · May 20, 12:43 · [Discussion](https://news.ycombinator.com/item?id=48206768)

**Background**: Social media platforms like Meta often comply with local laws to maintain access to markets, even when those laws conflict with human rights principles. Saudi Arabia and the UAE have strict regulations on online speech, penalizing criticism of the government or ruling families.

**Discussion**: Commenters expressed skepticism, with some arguing Meta has no choice but to comply or face worse alternatives, while others condemned the company for prioritizing growth over principles. One user noted that social media was once promised to spread democracy, but this action shows otherwise.

**Tags**: `#censorship`, `#human rights`, `#Meta`, `#geopolitics`, `#social media`

---

<a id="item-5"></a>
## [Blog Post Lists Surprising C Undefined Behaviors](https://blog.habets.se/2026/05/Everything-in-C-is-undefined-behavior.html) ⭐️ 8.0/10

A blog post titled 'Everything in C is undefined behavior' went viral on Hacker News, listing various surprising undefined behaviors in the C programming language, sparking extensive discussion among systems programmers. This discussion highlights the deep pitfalls of C programming, especially for performance-critical and safety-critical systems, and underscores the ongoing tension between compiler optimizations and programmer intent. The blog post's examples include volatile access causing undefined behavior due to unsequenced side effects, and unaligned pointer casting being UB even before dereferencing. Commenters note that many examples are conditional on input or circumstances, similar to stack overflow in any language.

hackernews · lycopodiopsida · May 20, 06:07 · [Discussion](https://news.ycombinator.com/item?id=48203698)

**Background**: Undefined behavior (UB) in C means the language standard imposes no requirements on program behavior; the compiler may do anything, including producing unexpected results or crashing. This allows aggressive optimizations but can introduce subtle bugs. Many C programmers rely on common compiler behaviors, which may differ from the standard.

**Discussion**: Commenters expressed mixed opinions: some criticized the article for sensationalism and missing deeper UB examples, while others appreciated it as a conversation starter. One user humorously outlined the five stages of learning about UB (denial, anger, bargaining, depression, acceptance). The discussion also delved into technical nuances of volatile and unaligned access.

**Tags**: `#C`, `#undefined behavior`, `#programming languages`, `#compilers`, `#systems programming`

---

<a id="item-6"></a>
## [EU launches Wero, sovereign payment alternative to Visa/Mastercard](https://www.lesnumeriques.com/banque-en-ligne/adieu-visa-et-mastercard-130-millions-d-europeens-basculent-vers-un-paiement-100-souverain-des-2026-n250918.html) ⭐️ 8.0/10

The European Payments Initiative launched Wero on July 2, 2024, a mobile payment system aiming to replace national solutions like iDEAL, Bizum, and Giropay, targeting 130 million users by 2026. Wero offers a sovereign European alternative to US-dominated card networks Visa and Mastercard, enhancing digital sovereignty and reducing dependency on non-EU payment infrastructure. Wero enables account-to-account payments in under 10 seconds across borders, and consolidates fragmented national systems; however, it initially focuses on online payments and may not affect in-store or contactless payments immediately.

hackernews · healsdata · May 20, 13:02 · [Discussion](https://news.ycombinator.com/item?id=48207004)

**Background**: Currently, each EU country often has its own mobile payment system, such as iDEAL in the Netherlands or Bizum in Spain, which are not interoperable across borders. Visa and Mastercard dominate transaction processing, raising concerns about data sovereignty and fees. Wero, backed by the European Payments Initiative and 16 financial institutions, aims to create a unified European payment method.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Wero_(payment)">Wero ( payment ) - Wikipedia</a></li>
<li><a href="https://wero-wallet.eu/">Wero - European payment solution</a></li>
<li><a href="https://www.checkout.com/blog/wero-payments">What is Wero and how does it work?</a></li>

</ul>
</details>

**Discussion**: Commenters generally support the idea of a European payment system, with some praising iDEAL as a gold standard. However, several note that the headline is misleading as it describes only online payments, not in-store, and that direct debit cards are still often Visa/Mastercard-powered. There is also humor about the name 'Wero' coming from 'we-ro' (sharing your euro).

**Tags**: `#fintech`, `#payments`, `#EU`, `#digital sovereignty`, `#online banking`

---

<a id="item-7"></a>
## [uv 0.11.15 released with security fixes and enhancements](https://github.com/astral-sh/uv/releases/tag/0.11.15) ⭐️ 7.0/10

Astral released uv 0.11.15 on 2026-05-18, fixing two security vulnerabilities: a TAR parser differential (GHSA-3cv2-h65g-fgmm) and a scripts directory escape (GHSA-4gg8-gxpx-9rph). It also introduces TOML v1.1 to v1.0 backwards compatibility for source distributions and support for Azure request signing. As a widely used Python package manager, uv's security fixes are critical for protecting users from potential attacks like symlink traversal or arbitrary file writes. The enhancements improve compatibility with modern Python packaging standards and cloud workflows. The TAR parser differential could allow an attacker to write files outside the intended directory via crafted tar entries, while the scripts directory escape prevented path traversal in script entry points. Additional changes include stricter validation of wheel filenames and rejection of empty package names.

github · github-actions[bot] · May 18, 19:59

**Background**: uv is a fast, Rust-based Python package manager that replaces pip and pip-tools. A TAR parser differential is a vulnerability where symlinks or path components in a tar archive can trick the extraction process to write files outside the target directory, leading to arbitrary file overwrite. Scripts directory escape refers to path traversal in the scripts directory, where entry points could break out of the intended sandbox.

<details><summary>References</summary>
<ul>
<li><a href="https://www.man7.org/linux/man-pages/man1/tar.1.html">tar (1) - Linux manual page - man7.org</a></li>
<li><a href="https://docs.astral.sh/uv/guides/scripts/">Running scripts | uv</a></li>
<li><a href="https://en.wikipedia.org/wiki/TOML">TOML - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#package-management`, `#security`, `#python`, `#release`

---

<a id="item-8"></a>
## [Google fights manipulation of AI search results](https://www.bbc.com/future/article/20260519-google-tackles-attempts-to-hack-its-ai-results) ⭐️ 7.0/10

Google is quietly combating attempts to manipulate its AI-generated search results, particularly through adversarial techniques that trick AI Overviews. This matters because manipulated AI search results could spread misinformation or influence financial and health decisions, eroding trust in Google's core product. It also signals a new stage in the ongoing battle between search engines and SEO spammers. The manipulation involves feeding false content to Google's AI, akin to black-hat SEO for AI-generated summaries. While Google's SpamBrain anti-spam system could be deployed, critics remain skeptical given the company's historical struggles with web spam.

hackernews · tigerlily · May 20, 10:57 · [Discussion](https://news.ycombinator.com/item?id=48205782)

**Background**: Google has long battled spam and SEO manipulation in its search results, developing systems like SpamBrain—an AI-based spam detection engine. With the introduction of AI Overviews that generate summaries from web content, new attack vectors have emerged where adversaries craft content to alter those summaries. This mirrors past tactics but targets the AI layer directly.

<details><summary>References</summary>
<ul>
<li><a href="https://spambrain.com/">Google SpamBrain</a></li>
<li><a href="https://blog.hubspot.com/marketing/black-hat-seo">What is black hat SEO? Understanding the risks</a></li>
<li><a href="https://www.searchenginejournal.com/seo-black-hat-techniques/180601/">13 Black Hat Techniques That Can Harm An SEO Campaign</a></li>

</ul>
</details>

**Discussion**: Community commenters express deep skepticism, noting Google's inability to fully eliminate spam since 2006. Some view this as a minor issue based on the trivial example given, while others see it as the inevitable next phase of SEO, with an endless cat-and-mouse cycle. A few question why Google isn't leveraging its vast web reliability knowledge.

**Tags**: `#AI`, `#Google`, `#search`, `#spam`, `#SEO`

---

<a id="item-9"></a>
## [Curated Index of Archived FiveThirtyEight Articles](https://fivethirtyeightindex.com/) ⭐️ 7.0/10

A curated index of archived FiveThirtyEight articles on the Internet Archive has been created at fivethirtyeightindex.com in response to ABC News/Disney removing thousands of articles from the site. This archive preserves the journalistic work of FiveThirtyEight, a major data journalism site, and ensures public access to historical articles that were deleted by the new owners. The index was created by Ben Welsh, a reporter and programmer at Reuters, and while many archived pages work, some interactive visualizations like the gun deaths visualization are broken due to missing JavaScript or APIs.

hackernews · ChocMontePy · May 20, 01:34 · [Discussion](https://news.ycombinator.com/item?id=48201973)

**Background**: FiveThirtyEight was a data journalism website founded by Nate Silver, known for its statistical analysis of politics and sports. In 2023, after being acquired by Disney, ABC News removed most of the site's articles, sparking concerns about digital preservation of journalism. The Internet Archive's Wayback Machine captures snapshots of web pages, and this index helps navigate the archived content.

**Discussion**: Community comments highlight the significance of archiving, with one user noting that thousands of articles vanished; others discuss Nate Silver's personal site as an alternative. There is disappointment that many interactive visualizations are broken in the archived version, such as the gun deaths interactive.

**Tags**: `#digital preservation`, `#journalism`, `#fivethirtyeight`, `#internet archive`, `#data journalism`

---

<a id="item-10"></a>
## [Japan's mass allergies traced to 1950s reforestation project](https://www.bbc.com/future/article/20260515-the-1950s-blunder-which-causes-mass-hay-fever-in-japan) ⭐️ 6.0/10

A BBC Future article reveals that Japan's severe hay fever epidemic, affecting tens of millions, is linked to a post-war reforestation project that planted vast monocultures of sugi (cedar) and hinoki (cypress) trees in the 1950s and 1960s. This highlights how well-intentioned environmental policies can have unintended long-term public health consequences, affecting millions annually and straining healthcare systems. The forests were intended to be harvested gradually but cheaper imports led to them being left untouched, causing massive pollen release each spring. The article notes that the government is now trying to convert these monocultures back to mixed forests.

hackernews · ranit · May 20, 01:43 · [Discussion](https://news.ycombinator.com/item?id=48202047)

**Background**: After World War II, Japan faced deforestation and soil erosion, prompting a large-scale reforestation program using fast-growing sugi and hinoki trees for timber. The trees take 30-50 years to mature and start producing large amounts of pollen. By the time they were ready for harvest, Japan's economy had shifted to cheaper imported wood, so the trees remained standing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Hay_fever_in_Japan">Hay fever in Japan - Wikipedia</a></li>
<li><a href="https://www.bbc.com/future/article/20260515-the-1950s-blunder-which-causes-mass-hay-fever-in-japan">Japan is gripped by mass allergies. A 1950s project is to blame</a></li>

</ul>
</details>

**Discussion**: Comments discuss parallels with German monoculture forests and question why treatments like acupuncture weren't mentioned. Some users point out the original plan was for gradual harvesting, but economic factors prevented it.

**Tags**: `#environment`, `#health`, `#Japan`, `#forestry`, `#history`

---

<a id="item-11"></a>
## [Simon Willison Analyzes Gemini Spark and Antigravity at Google I/O](https://simonwillison.net/2026/May/20/google-io/#atom-everything) ⭐️ 6.0/10

Simon Willison discusses Google I/O announcements, highlighting Gemini Spark as a personal AI agent that runs on Gemini 3.5 Flash and Antigravity, but he notes his policy prevents in-depth analysis until the product is generally available. Gemini Spark represents a significant step toward personal AI agents integrated with Google's ecosystem, but security concerns around prompt injection and data privacy remain critical as it handles sensitive user data. Gemini Spark connects with Gmail, Calendar, Drive, and other Google apps, running in isolated ephemeral VMs with enterprise-grade security. Meanwhile, Google is replacing the open source Gemini CLI with the closed source Antigravity CLI by June 18th.

rss · Simon Willison · May 20, 15:32

**Background**: Simon Willison is a well-known figure in the developer community who often writes about AI and LLMs. He has a policy of only writing about products he can try himself, which limits his analysis of preview-only announcements like Gemini Spark. Gemini Spark is described as a 24/7 personal AI agent, and Antigravity is a set of tools including a CLI and SDK.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/products/gemini-app/next-evolution-gemini-app/">The Gemini app becomes more agentic, delivering proactive, 24/7 help</a></li>
<li><a href="https://gemini.google/overview/agent/spark/">Gemini Spark – Your 24/7 personal AI agent for productivity</a></li>

</ul>
</details>

**Tags**: `#Google I/O`, `#AI Agent`, `#Gemini Spark`, `#Google`

---

<a id="item-12"></a>
## [Last 6 months of LLMs in a 5-minute talk](https://simonwillison.net/2026/May/19/5-minute-llms/#atom-everything) ⭐️ 6.0/10

Simon Willison presented a five-minute lightning talk at PyCon US 2026 summarizing the last six months of developments in large language models, including annotated slides. The talk highlights the November 2025 inflection point and the rapid shift in which model was considered 'best' among Anthropic, OpenAI, and Google. This summary provides a concise, accessible update for developers and AI enthusiasts to quickly grasp the rapid pace of LLM evolution. It helps the community stay informed without requiring deep technical analysis. The talk notes that the 'best' model changed hands five times between November 2025 and May 2026, starting with Claude Sonnet 4.5 and passing through GPT-5.1, Gemini 3, GPT-5.1 Codex Max, and Claude Opus. Willison uses a custom 'pelican riding a bicycle' SVG test to illustrate model differences.

rss · Simon Willison · May 19, 01:09

**Background**: Large language models have been evolving rapidly, with multiple major releases in late 2025. The November 2025 inflection point marked a period of intense competition among top AI labs. Willison's annotated presentation tool allows him to create slides with accompanying notes for easy sharing.

**Tags**: `#LLMs`, `#AI`, `#PyCon`, `#Lightning Talk`, `#Summary`

---