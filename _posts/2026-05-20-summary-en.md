---
layout: default
title: "Horizon Summary: 2026-05-20 (EN)"
date: 2026-05-20
lang: en
---

> From 28 items, 12 important content pieces were selected

---

1. [EU launches Wero, sovereign payment for 130M Europeans by 2026](#item-1) ⭐️ 9.0/10
2. [Qwen3.7-Max: Alibaba's New Frontier Open-Source Model](#item-2) ⭐️ 8.0/10
3. [Mozilla Deprecates Asm.js, WebAssembly Takes Over](#item-3) ⭐️ 8.0/10
4. [Meta blocks human rights accounts in Saudi Arabia, UAE](#item-4) ⭐️ 8.0/10
5. [Blog post explores pervasive undefined behavior in C](#item-5) ⭐️ 8.0/10
6. [Google announces Gemini 3.5 Flash with significant price hikes](#item-6) ⭐️ 8.0/10
7. [uv 0.11.15 Released with Critical Security Patches](#item-7) ⭐️ 7.0/10
8. [Archived FiveThirtyEight Index Launched After Disney Removal](#item-8) ⭐️ 7.0/10
9. [Simon Willison's Lightning Talk: Six Months of LLM Progress](#item-9) ⭐️ 7.0/10
10. [Japan's 1950s forestry project blamed for mass allergies](#item-10) ⭐️ 6.0/10
11. [Google I/O 2026: Gemini Spark and Antigravity Steal the Show](#item-11) ⭐️ 6.0/10
12. [llm-gemini 0.32 Adds Gemini 3.5 Flash Support](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [EU launches Wero, sovereign payment for 130M Europeans by 2026](https://www.lesnumeriques.com/banque-en-ligne/adieu-visa-et-mastercard-130-millions-d-europeens-basculent-vers-un-paiement-100-souverain-des-2026-n250918.html) ⭐️ 9.0/10

The European Union is launching Wero, a unified sovereign payment system that will replace Visa and Mastercard for 130 million Europeans starting in 2026, consolidating fragmented online payment methods across member states. This shift reduces Europe's dependence on US payment networks, strengthens digital sovereignty, and simplifies cross-border transactions, potentially lowering fees and increasing data privacy for consumers and merchants. Wero initially focuses on online payments and peer-to-peer transfers, not in-store transactions; it builds on existing national systems like iDeal (Netherlands) and Bizum (Spain). Direct debit cards, often Visa/Mastercard-backed, will remain in use for contactless payments.

hackernews · healsdata · May 20, 13:02 · [Discussion](https://news.ycombinator.com/item?id=48207004)

**Background**: Wero is a European payment initiative designed to create a sovereign alternative to US card networks Visa and Mastercard. It leverages the existing banking infrastructure to redirect users to their bank's security system for authorization, eliminating the need to enter card details on merchant sites. The system aims to reduce fragmentation in the EU's digital payment landscape.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Wero_(payment)">Wero (payment) - Wikipedia</a></li>
<li><a href="https://wero-wallet.eu/pay-online">Wero - Pay Online</a></li>
<li><a href="https://banking.vision/en/development-wero-2025-2026/">Wero 2025/2026 – The European payment engine is picking up ...</a></li>

</ul>
</details>

**Discussion**: Community sentiment is generally positive, with many praising the move toward sovereignty and improved security. However, some commenters note the headline is misleading as Wero initially covers only online payments, not in-store, and that direct debit cards still rely on Visa/Mastercard. A few humorous remarks about the name 'Wero' (sharing 'you-ro') were also shared.

**Tags**: `#fintech`, `#European sovereignty`, `#payment systems`, `#digital payments`, `#regulatory impact`

---

<a id="item-2"></a>
## [Qwen3.7-Max: Alibaba's New Frontier Open-Source Model](https://qwen.ai/blog?id=qwen3.7) ⭐️ 8.0/10

Alibaba has released Qwen3.7-Max, an open-source large language model that claims state-of-the-art non-hallucination rates, surpassing models like Opus 4.7 and GPT-5.5 on the AA-omniscience benchmark. This release pushes the frontier of open-source AI, offering a competitive alternative to proprietary models. It could lower barriers for businesses and developers to deploy high-performance, low-hallucination models. The model achieves SOTA non-hallucination rates according to the AA-omniscience benchmark, but actual performance across other benchmarks may vary. Community members note that hosting via proxy services like OpenRouter may have throttling issues.

hackernews · kevinsimper · May 20, 10:35 · [Discussion](https://news.ycombinator.com/item?id=48205626)

**Background**: Qwen is a series of large language models developed by Alibaba, ranging from 0.5B to 72B parameters, including Mixture-of-Experts variants. Hallucination rates measure how often a model generates false or fabricated information; lower rates are critical for reliable AI applications.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/Qwen/Qwen2-7B">Qwen / Qwen 2-7B · Hugging Face</a></li>
<li><a href="https://openrouter.ai/qwen">Qwen API and Models | OpenRouter</a></li>
<li><a href="https://github.com/vectara/hallucination-leaderboard/">Hallucination Leaderboard - GitHub</a></li>

</ul>
</details>

**Discussion**: Comments express excitement about the model's capabilities and its potential as a free alternative to Claude Code. Some users wish for US-based hosting options due to geopolitical concerns, while others discuss practical deployment issues such as throttling on proxy services.

**Tags**: `#AI`, `#open-source`, `#large language model`, `#Qwen`, `#machine learning`

---

<a id="item-3"></a>
## [Mozilla Deprecates Asm.js, WebAssembly Takes Over](https://spidermonkey.dev/blog/2026/05/20/saying-goodbye-to-asmjs.html) ⭐️ 8.0/10

Mozilla's SpiderMonkey team announced the deprecation of asm.js in Firefox, as WebAssembly has fully superseded it. The feature will be removed in a future release. Asm.js pioneered near-native performance in browsers and directly led to the development of WebAssembly. Its deprecation marks the end of a foundational technology and confirms WebAssembly as the universal standard for high-performance web applications. Asm.js is a strict subset of JavaScript used as a compilation target for C/C++ via Emscripten, first supported in Firefox 22. WebAssembly, a binary format with faster parsing and stronger security, became a W3C recommendation in 2019 and is now supported in all major browsers.

hackernews · eqrion · May 20, 12:01 · [Discussion](https://news.ycombinator.com/item?id=48206340)

**Background**: Asm.js was created by Mozilla in 2013 to allow C/C++ code to run in browsers at near-native speeds, using a subset of JavaScript that engines could optimize ahead-of-time. It proved the concept of high-performance web apps, leading to the creation of WebAssembly, a portable binary format that uses a common virtual machine. WebAssembly offers smaller file sizes, faster decoding, and a clear security model, making it the preferred choice for performance-critical web content.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Asm.js">Asm.js</a></li>
<li><a href="https://en.wikipedia.org/wiki/WebAssembly">WebAssembly</a></li>

</ul>
</details>

**Discussion**: Community comments reflect a bittersweet sentiment: some developers nostalgic about asm.js demos like Unreal Engine in the browser, while others highlight its practical legacy, such as Figma's initial reliance on asm.js. There are also concerns about WebAssembly's current limitations, like the need for shims to call Web APIs, and historical debates over NaCl vs. asm.js.

**Tags**: `#asm.js`, `#WebAssembly`, `#web platform`, `#SpiderMonkey`, `#deprecation`

---

<a id="item-4"></a>
## [Meta blocks human rights accounts in Saudi Arabia, UAE](https://www.alqst.org/ar/posts/1190) ⭐️ 8.0/10

Meta has blocked or restricted access to human rights-related accounts and content in Saudi Arabia and the United Arab Emirates, limiting their reach to local audiences. This action highlights the ongoing tension between global social media platforms' commitment to free expression and their need to comply with local laws and government pressures in authoritarian countries. The report from ALQST indicates that Meta deliberately reduced visibility of human rights accounts, effectively censoring activists and organizations in these countries.

hackernews · giuliomagnifico · May 20, 12:43 · [Discussion](https://news.ycombinator.com/item?id=48206768)

**Background**: Social media platforms like Meta are often caught between advocating for free speech and adhering to local regulations. In countries like Saudi Arabia and the UAE, strict cybercrime laws and anti-terrorism legislations can be used to restrict dissent, forcing platforms to either comply or risk being blocked entirely.

**Discussion**: Commenters expressed mixed reactions, with some arguing that Meta had no choice but to comply or face being banned in those countries, while others criticized the company for prioritizing profits over principles. A few users expressed personal boycotts of Meta services, and one compared the platform to 'vampires we invited in.'

**Tags**: `#platform censorship`, `#free speech`, `#Meta`, `#human rights`, `#social media`

---

<a id="item-5"></a>
## [Blog post explores pervasive undefined behavior in C](https://blog.habets.se/2026/05/Everything-in-C-is-undefined-behavior.html) ⭐️ 8.0/10

A blog post titled 'Everything in C is undefined behavior' has been published, highlighting surprising and lesser-known instances of undefined behavior in the C programming language. The post has garnered significant community engagement with 396 points and 536 comments. Understanding undefined behavior is critical for C programmers and systems engineers, as it can lead to unpredictable program behavior and security vulnerabilities. This discussion underscores the importance of writing safe and portable C code. Community comments note that the article only scratches the surface; for instance, reading a volatile variable twice in a printf argument list is undefined behavior due to unsequenced side effects. Additionally, creating an unaligned pointer via casting is itself undefined behavior, not just the access.

hackernews · lycopodiopsida · May 20, 06:07 · [Discussion](https://news.ycombinator.com/item?id=48203698)

**Background**: Undefined behavior (UB) in C refers to code constructs that the C standard does not define, allowing compilers to assume they never occur and optimize aggressively. Common sources include signed integer overflow, strict aliasing violations, and accessing memory through improperly aligned pointers. The concept of sequence points defines when side effects must be completed, and violations can lead to UB.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pointer_aliasing">Aliasing (computing) - Wikipedia</a></li>
<li><a href="https://stackoverflow.com/questions/4176328/what-are-sequence-points-and-how-do-they-relate-to-undefined-behavior">What are sequence points, and how do they relate to undefined ... Usage example</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed: some argue the article sensationalizes UB and fails to capture the real intricacies, while others appreciate the awareness it raises. One comment humorously outlines the 'five stages of learning about UB', and another warns that overstating UB harms novices' understanding of actual C pitfalls.

**Tags**: `#C`, `#undefined behavior`, `#programming languages`, `#compilers`, `#safety`

---

<a id="item-6"></a>
## [Google announces Gemini 3.5 Flash with significant price hikes](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-5/) ⭐️ 8.0/10

Google has announced Gemini 3.5 Flash, the latest iteration of its fast and cost-efficient Flash model series. The new model comes with a substantial price increase, with input token costs rising from $0.50 to $1.50 per million tokens and output tokens from $3.00 to $9.00 per million tokens compared to the previous Gemini 3.0 Flash Preview. This pricing change marks a notable shift in Google's strategy, as Gemini 3.5 Flash now costs nearly as much as the larger Gemini 2.5 Pro model, potentially altering its value proposition for developers. The community is actively debating whether the performance gains justify the cost, which could influence adoption in agentic and coding workflows. The model's knowledge cutoff is early 2025, so enabling web search is recommended for current events. Community members have inferred technical details, such as parameter counts, from the hardware constraints of serving on TPU 8i, though Google has not officially disclosed specifications.

hackernews · spectraldrift · May 19, 17:43 · [Discussion](https://news.ycombinator.com/item?id=48196570)

**Background**: Google's Flash models are designed to offer frontier-level intelligence at lower latency and cost, optimized for real-time tasks like coding and agentic loops. The pricing of large language models (LLMs) is typically based on token usage, with output tokens costing 3-10x more than input tokens due to the computational demand of generation. This release continues the trend of rapid model iteration, but the price increase contrasts with the usual expectation of decreasing costs per token over time.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-5/">Gemini 3 . 5 : frontier intelligence with action</a></li>
<li><a href="https://deepmind.google/models/gemini/flash/">Gemini 3 . 5 Flash — Google DeepMind</a></li>
<li><a href="https://ai.google.dev/gemini-api/docs/models/gemini-3.5-flash">Gemini 3 . 5 Flash | Gemini API | Google AI for Developers</a></li>

</ul>
</details>

**Discussion**: The community comments reflect a mix of surprise and analysis. Several users pointed out the 3x price increase, with one noting that Gemini 3.5 Flash now costs similar to Gemini 2.5 Pro. Others discussed model performance, with comparisons showing that Gemini 3.5 Flash uses significantly fewer tokens than the older 3.1 Pro for certain tasks. There was also discussion about the model's cutoff date and the lack of official technical disclosure, with some users attempting to infer parameter counts from hardware constraints.

**Tags**: `#AI`, `#Gemini`, `#Google`, `#LLM pricing`, `#Machine Learning`

---

<a id="item-7"></a>
## [uv 0.11.15 Released with Critical Security Patches](https://github.com/astral-sh/uv/releases/tag/0.11.15) ⭐️ 7.0/10

Astral's uv package manager version 0.11.15 was released on May 18, 2026, fixing a TAR parser differential vulnerability (GHSA-3cv2-h65g-fgmm) and an entry point escape issue (GHSA-4gg8-gxpx-9rph). It also includes enhancements like TOML v1.1 backward compatibility, Azure request signing support, and stricter wheel filename validation. This release is important because uv is a widely used Python package manager; the security fixes protect users from potential arbitrary code execution or file manipulation during package installation. The TOML v1.1 backward compatibility ensures smooth adoption of the latest TOML standard in Python packaging. The TAR parser differential vulnerability in the forked tokio-tar library could allow crafted archive headers to bypass checks. The entry point escape fix enforces that scripts cannot be placed outside designated directories, preventing code execution. Performance improvements include avoiding JSON manifest parsing when a local Python is available and optimizing async ZIP writing.

github · github-actions[bot] · May 18, 19:59

**Background**: uv is a fast Python package manager and resolver written in Rust, developed by Astral. It aims to replace tools like pip and pip-tools. The TAR parser differential is a type of vulnerability where specially crafted TAR archives can cause the parser to behave differently than expected, potentially leading to security bypasses. The entry point escape occurs when scripts declared in package metadata are written to locations outside the intended 'scripts' directory, which could allow arbitrary code execution.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/astral-sh/tokio-tar">GitHub - astral-sh/tokio-tar: A tar archive reading/writing ...</a></li>
<li><a href="https://discuss.python.org/t/adopting-toml-1-1/105624">Adopting TOML 1.1? - Coordination - Discussions on Python.org</a></li>

</ul>
</details>

**Tags**: `#uv`, `#python`, `#package-manager`, `#security`, `#release`

---

<a id="item-8"></a>
## [Archived FiveThirtyEight Index Launched After Disney Removal](https://fivethirtyeightindex.com/) ⭐️ 7.0/10

A website called fivethirtyeightindex.com has been launched to index thousands of FiveThirtyEight articles archived via the Internet Archive, after Disney and ABC removed the original content from the web. This incident underscores the fragility of digital journalism and the importance of web archiving, as media consolidation can lead to the erasure of valuable journalistic work. It also empowers readers and researchers to access content that would otherwise be lost. The index aggregates links from the Wayback Machine, but many interactive visualizations, such as the gun deaths visualization and the P-hacking interactive, are broken in the archived versions. The site was created by Ben Welsh, a Reuters reporter and former data journalist.

hackernews · ChocMontePy · May 20, 01:34 · [Discussion](https://news.ycombinator.com/item?id=48201973)

**Background**: FiveThirtyEight, a data-driven journalism site founded by Nate Silver, was acquired by Disney in 2013. In 2023, Disney/ABC removed thousands of articles from the site, leading to significant loss of content. The Internet Archive is a non-profit library that preserves web pages through its Wayback Machine, which has archived more than 1 trillion web captures. Web archiving is essential for preserving digital culture and ensuring long-term access to online information.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Internet_Archive">Internet Archive</a></li>
<li><a href="https://en.wikipedia.org/wiki/Web_archiving">Web archiving</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted the irony that Nate Silver may benefit from the removal, as readers flock to his personal site. Others noted that many interactive visualizations are broken in the archives, which is a sad loss. Some also appreciated the work of Ben Welsh in creating the index.

**Tags**: `#digital preservation`, `#media consolidation`, `#web archiving`, `#FiveThirtyEight`, `#journalism`

---

<a id="item-9"></a>
## [Simon Willison's Lightning Talk: Six Months of LLM Progress](https://simonwillison.net/2026/May/19/5-minute-llms/#atom-everything) ⭐️ 7.0/10

Simon Willison presented a five-minute lightning talk at PyCon US 2026 summarizing key LLM developments from November 2025 to May 2026, including five changes in the 'best' model among Anthropic, OpenAI, and Google. This curated overview provides a quick yet comprehensive snapshot of rapid advancements in LLMs, especially in coding capabilities, helping developers stay current with the fast-moving AI landscape. Willison used his 'Generate an SVG of a pelican riding a bicycle' test to demonstrate model capabilities, noting that the test is fair because it was not a training task for any lab.

rss · Simon Willison · May 19, 01:09

**Background**: The talk highlighted the November 2025 inflection point, where coding models such as GPT-5.1, Gemini 3, and Claude Opus rapidly succeeded each other as the top model. Willison's annotated presentation tool, built with LLM assistance, allows him to create interactive slide summaries with commentary.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/tags/annotated-talks/">Simon Willison on annotated-talks</a></li>
<li><a href="https://tools.simonwillison.net/annotated-presentations">Annotated Presentation Creator</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#AI`, `#Python`, `#PyCon`, `#lightning talk`

---

<a id="item-10"></a>
## [Japan's 1950s forestry project blamed for mass allergies](https://www.bbc.com/future/article/20260515-the-1950s-blunder-which-causes-mass-hay-fever-in-japan) ⭐️ 6.0/10

A BBC investigation reveals that Japan's severe hay fever epidemic, affecting over 42% of the population, stems from post-war monoculture forestry projects in the 1950s and 1960s that planted vast areas with sugi (cedar) and hinoki (cypress) trees. This historical policy blunder now causes widespread seasonal allergies, disrupting daily life and the economy, and serves as a cautionary tale about long-term unintended consequences of large-scale environmental interventions. The trees were intended to be gradually harvested, but cheaper imports from Malaysia and other countries made domestic logging uneconomical, leaving the monoculture plantations to mature and release massive pollen clouds annually.

hackernews · ranit · May 20, 01:43 · [Discussion](https://news.ycombinator.com/item?id=48202047)

**Background**: After World War II, Japan embarked on a massive reforestation program to meet timber demands for reconstruction. The government encouraged planting of fast-growing sugi and hinoki trees, often in monoculture stands. These trees now cover about 12% of Japan's land area and produce copious lightweight pollen that drifts into urban areas, triggering hay fever.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bbc.com/future/article/20260515-the-1950s-blunder-which-causes-mass-hay-fever-in-japan">Japan is gripped by mass allergies. A 1950s project is to blame</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hay_fever_in_Japan">Hay fever in Japan - Wikipedia</a></li>
<li><a href="https://bnn-news.com/japan-struggles-with-allergies-pollen-is-to-blame-280419">Japan struggles with allergies; pollen is to blame - Baltic News Network</a></li>

</ul>
</details>

**Discussion**: Comments highlight the irony that the trees were meant to be harvested but cheap imports made it unprofitable, and compare Japan's situation to German monoculture forests which also produce pollen clouds but seemingly cause fewer allergies. Some discuss alternative treatments like acupuncture for allergy relief.

**Tags**: `#environment`, `#allergies`, `#Japan`, `#history`, `#forestry`

---

<a id="item-11"></a>
## [Google I/O 2026: Gemini Spark and Antigravity Steal the Show](https://simonwillison.net/2026/May/20/google-io/#atom-everything) ⭐️ 6.0/10

Google announced Gemini Spark, a personal AI agent that connects natively with Google apps, and introduced Antigravity, a closed-source agent harness that replaces the open-source Gemini CLI. Gemini Spark runs on Gemini 3.5 Flash and Antigravity, with enterprise-grade security through isolated ephemeral VMs. Gemini Spark represents Google's push into autonomous AI agents that can act on behalf of users across Workspace, potentially transforming productivity. However, the shift from open-source to closed-source tooling and security concerns around prompt injection could impact developer trust and enterprise adoption. Gemini Spark runs on Gemini 3.5 Flash and Antigravity, with Antigravity comprising a desktop app, CLI (Go), Python SDK, and VS Code fork. Google announced that the open-source Gemini CLI (TypeScript, Apache 2.0) will stop working with subscription plans on June 18, 2026, replaced by the closed-source Antigravity CLI.

rss · Simon Willison · May 20, 15:32

**Background**: Gemini is Google's family of multimodal large language models, succeeding LaMDA and PaLM. Gemini Spark is a new agentic product that automates tasks in Gmail, Calendar, Drive, etc., leveraging Google's cloud infrastructure. Antigravity is a harness that enables agent execution, and its CLI tool is now closed-source, contrasting with the previously open Gemini CLI.

<details><summary>References</summary>
<ul>
<li><a href="https://gemini.google/overview/agent/spark/">Gemini Spark – Your 24/7 personal AI agent for productivity</a></li>
<li><a href="https://blog.google/innovation-and-ai/products/gemini-app/next-evolution-gemini-app/">The Gemini app becomes more agentic, delivering proactive, 24/7 help</a></li>
<li><a href="https://en.wikipedia.org/wiki/Gemini_Spark">Gemini Spark</a></li>

</ul>
</details>

**Tags**: `#Google I/O`, `#Gemini Spark`, `#AI agents`, `#personal assistant`, `#Google`

---

<a id="item-12"></a>
## [llm-gemini 0.32 Adds Gemini 3.5 Flash Support](https://simonwillison.net/2026/May/19/llm-gemini-2/#atom-everything) ⭐️ 6.0/10

Version 0.32 of the llm-gemini plugin adds support for Google's new Gemini 3.5 Flash model, enabling users to access it from the LLM command-line tool. This update allows LLM users to leverage the improved performance and cost-efficiency of Gemini 3.5 Flash, which is optimized for complex coding and agentic tasks. The only change in this release is the addition of the `gemini-3.5-flash` model; no other features or fixes are included.

rss · Simon Willison · May 19, 23:46

**Background**: LLM is an open-source command-line tool and Python library by Simon Willison that provides a unified interface to interact with various large language models. Gemini 3.5 Flash is Google's latest flash model offering sustained frontier-level intelligence with higher speed and lower cost, particularly effective for real-world tasks like rapid agentic loops and complex coding.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/simonw/llm">GitHub - simonw/llm: Access large language models from the ...</a></li>
<li><a href="https://deepmind.google/models/gemini/flash/">Gemini 3 . 5 Flash — Google DeepMind</a></li>

</ul>
</details>

**Tags**: `#llm`, `#gemini`, `#release`, `#plugin`

---