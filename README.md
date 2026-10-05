<link rel='stylesheet' href='//cdn.jsdelivr.net/npm/hack-font@3.3.0/build/web/hack-subset.css'>

# ૐ The humble hegumen Pafnuty here sets his hand to it ༀ

Engenheiro-filósofo cognoscente, busca profundidade, integrabilidade e sincronicidade em tudo o que faz. <br />
Cognizant engineer-philosopher, seeking depth, integrability, and synchronicity in everything he does. <br />
认知型的工程师-哲学家，追求深度、可整合性与万事万物的同步性。<br />

Engineer physicist turned software engineer. I build Lisp tooling, agent infrastructure and
knowledge systems, mostly in **Clojure** and **Go**, and I contribute upstream to the runtimes
and libraries I depend on.

- My <span style="color:#bf8ae2; font-family: 'Hack, monospace';">cyber corner</span>: [buddhilw.com](https://www.buddhilw.com/)
- My portfolio: [portfolio.buddhilw.com](https://portfolio.buddhilw.com/)

## Featured projects

| Project | What it is |
|---|---|
| [**hive-mcp**](https://github.com/hive-agi/hive-mcp) | MCP server for multi-agent coordination: persistent memory, a knowledge graph, swarms of agents and structural code navigation. The core of the [hive-agi](https://github.com/hive-agi) ecosystem. Write-up: [8-10x Faster Development with LLM Memory That Persists](https://www.buddhilw.com/posts-output/2026-01-20-hive-mcp/). |
| [**clojure-elisp**](https://github.com/BuddhiLW/clojure-elisp) | A Clojure dialect that compiles to Emacs Lisp, the way ClojureScript targets JavaScript. On [Clojars](https://clojars.org/io.github.buddhilw/clojure-elisp) and [MELPA](https://github.com/melpa/melpa/pull/10246). |
| [**desargues**](https://github.com/mentat-collective/desargues) | Emmy (computer algebra) meets Manim: animated mathematics and physics scenes, such as Emmy-derived double pendulums, from Clojure. Core contributor at [mentat-collective](https://github.com/mentat-collective). [Landing page](https://mentat.org/desargues). |
| [**keg**](https://github.com/BuddhiLW/keg) | Knowledge Exchange Graph CLI in Go: Zettelkasten nodes with a dex and tags, sealed (encrypted) nodes and [Open Knowledge Format](https://github.com/GoogleCloudPlatform/open-knowledge-format) export. |
| [**plato**](https://github.com/BuddhiLW/plato) | A deck is a Clojure value: a presentation engine over Reveal.js with Markdown, Org and EDN front ends and a native CLI. [Live demo](https://buddhilw.github.io/plato/). |
| [**tod**](https://github.com/BuddhiLW/tod) | Emacs themes and wallpapers that follow the sun and the seasons, written in ClojureElisp. |
| [**AutoPDF**](https://github.com/BuddhiLW/AutoPDF) | PDF generation from LaTeX templates with Go templating, as a CLI. |

More tools: [design-forge](https://github.com/BuddhiLW/design-forge) (design tokens to CSS with a WCAG contrast gate),
[vpn-kis](https://github.com/BuddhiLW/vpn-kis) (a strict VPN kill switch),
[cleanx](https://github.com/BuddhiLW/cleanx) (a local opsec auditor),
[Blobing](https://github.com/BuddhiLW/Blobing) (blogging with Cryogen).

### The hive-agi ecosystem

[hive-agi](https://github.com/hive-agi) is a family of Clojure libraries and addons built around hive-mcp. Highlights:
[bb-mcp](https://github.com/hive-agi/bb-mcp) (a lightweight MCP server in Babashka),
[lsp-mcp](https://github.com/hive-agi/lsp-mcp) and [clj-kondo-mcp](https://github.com/hive-agi/clj-kondo-mcp) (static analysis as MCP tools),
[hive-cppb](https://github.com/hive-agi/hive-cppb) (Collect → Promote → Pipeline → Boundary workflow macros),
[hive-events](https://github.com/hive-agi/hive-events) (re-frame patterns on the JVM),
[clj-qdrant](https://github.com/hive-agi/clj-qdrant) and [milvus-clj](https://github.com/hive-agi/milvus-clj) (vector database clients).

## Open source contributions

Merged upstream work, newest first:

- [**clojurust**](https://github.com/csm/clojurust/pulls?q=is%3Apr+author%3ABuddhiLW+is%3Amerged) (Clojure on Rust): 44 merged PRs, covering an nREPL server, `deftype` and the datatype macros, ad-hoc hierarchies, `future`, `clojure.pprint`, lazy sequences, the reader, and native extension loading for AOT builds.
- [**ClojureWasm**](https://github.com/clojurewasm/ClojureWasm/commits?author=BuddhiLW) (a JVM-free Clojure runtime in Zig): nREPL classpath resolution, REPL evaluation and analyzer fixes. I also maintain its [Homebrew tap](https://github.com/BuddhiLW/homebrew-tap).
- [**dirge**](https://github.com/dirge-code/dirge/pulls?q=is%3Apr+author%3ABuddhiLW+is%3Amerged) (agent harness in Rust): Claude-Code-compatible hooks, background tool calls, token usage reporting over ACP.
- [**ansatz**](https://github.com/replikativ/ansatz/pulls?q=is%3Apr+author%3ABuddhiLW+is%3Amerged) (dependently typed Clojure with a Lean 4 kernel): malli schema to type translation, codegen guards, Fressian export.
- [**zwasm**](https://github.com/zwasm/zwasm/pulls?q=is%3Apr+author%3ABuddhiLW+is%3Amerged) (WebAssembly runtime in Zig): component interface resolution, WASI preview 2 metadata hashes.
- [**konserve**](https://github.com/replikativ/konserve/pull/145), [**clojure-mcp**](https://github.com/bhauman/clojure-mcp/pull/139), [**mcp-clojure-sdk**](https://github.com/unravel-team/mcp-clojure-sdk/pull/4), [**hyperframes**](https://github.com/heygen-com/hyperframes/pull/3750), [**MELPA**](https://github.com/melpa/melpa/pull/10246), [**awesome-clojure**](https://github.com/razum2um/awesome-clojure/pull/189).

In review: [xtdb](https://github.com/xtdb/xtdb/pull/6122), [emmy](https://github.com/mentat-collective/emmy/pulls?q=is%3Apr+author%3ABuddhiLW) and [emmy-viewers](https://github.com/mentat-collective/emmy-viewers/pulls?q=is%3Apr+author%3ABuddhiLW), [cljs-ajax](https://github.com/JulianBirch/cljs-ajax/pulls?q=is%3Apr+author%3ABuddhiLW), [re-frame-10x](https://github.com/day8/re-frame-10x/pull/426), [cloture](https://github.com/ruricolist/cloture/pulls?q=is%3Apr+author%3ABuddhiLW), [kontor](https://github.com/replikativ/kontor/pull/40), [cloffeine](https://github.com/AppsFlyer/cloffeine/pull/16), [bonzai](https://github.com/rwxrob/bonzai/pull/305).

### Past experiences
- Orasis Holding (Independent Contract);
- Lupo S.A. (Independent Contract);
- Flow Finance (CLT);
- Café do Bem O.N.G. (Volunteer);
- Bidding Prices Data Analysis (Independent Contract);
- Algorithmic Trading (Independent Contract);
- FACTI, Gov. Br. (CLT);

### Languages and tools

[<img align="left" alt="GNU/Linux" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/linux/linux.png" />][github]
[<img align="left" alt="Emacs" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/emacs/emacs.png" />][github]
[<img align="left" alt="Clojure" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/clojure/clojure.png" />][github]
[<img align="left" alt="Go" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/go/go.png" />][github]
[<img align="left" alt="Rust" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/rust/rust.png" />][github]
[<img align="left" alt="Elm" width="26px" src="https://avatars.githubusercontent.com/u/20698192?s=200&v=4" />][github]
[<img align="left" alt="JavaScript" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" />][github]
[<img align="left" alt="Python" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" />][github]
[<img align="left" alt="Julia" width="26px" src="https://raw.githubusercontent.com/github/explore/49e13f12be05e7e3f3616bb7a5030d70b259f320/topics/julia/julia.png" />][github]
[<img align="left" alt="Reagent" width="90px" src="https://github.com/reagent-project/reagent/raw/master/logo/logo-text.png" />][github]
<br />
<br />

### Connect with me

[<img align="left" alt="buddhilw.com" width="22px" src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" />][website]
[<img align="left" alt="buddhilw | Github" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v4/icons/github.svg"/>][github]
[<img align="left" alt="buddhilw | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v4/icons/linkedin.svg" />][linkedin]
<br />

[website]: https://buddhilw.com
[linkedin]: https://www.linkedin.com/in/pedro-g-branquinho/
[github]: https://github.com/BuddhiLW

### Support

<div>
<b>You can support me by making donations:</b> <a href="https://liberapay.com/BuddhiLittleWhite/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a>
<br />
<br />

Monero wallet: 82abdyrh6XwAxwJWLFYnkWV9oxPi8fphyNhGgQoEhvmJc3L5ZE5449NEcjvadhwTCKF2oMe7NtwLa71kthKVcrcp95ACZtt
</div>

### Stats
[![BuddhiLW's GitHub stats](https://github-readme-stats.vercel.app/api?username=BuddhiLW&show_icons=true&theme=dracula)](https://github.com/anuraghazra/github-readme-stats)

Use this layout under:
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
