A fast, secure MCP server that extends its capabilities through WebAssembly plugins.

## Available Plugins

We maintain several plugins to get you started:

### V1 Plugins

These plugins use the v1 plugin interface. While still supported, new plugins should use the v2 interface.

- [time](https://github.com/hyper-mcp-rs/time-plugin): Get current time and do time calculations (Rust)
- [qr_code](https://github.com/hyper-mcp-rs/qr-code-plugin): Generate QR codes (Rust)
- [hash](https://github.com/hyper-mcp-rs/hash-plugin): Generate various types of hashes (Rust)
- [myip](https://github.com/hyper-mcp-rs/myip-plugin): Get your current IP (Rust)
- [crypto_price](https://github.com/hyper-mcp-rs/crypto-price-plugin): Get cryptocurrency prices (Go)
- [fs](https://github.com/hyper-mcp-rs/fs-plugin): File system operations (Rust)
- [github](https://github.com/hyper-mcp-rs/github-plugin): GitHub plugin (Go)
- [eval_py](https://github.com/hyper-mcp-rs/eval-py-plugin): Evaluate Python code with RustPython (Rust)
- [memory](https://github.com/hyper-mcp-rs/memory-plugin): Let you store & retrieve memory, powered by SQLite (Rust)
- [crates-io](https://github.com/hyper-mcp-rs/crates-io-plugin): Get crate general information, check crate latest version (Rust)
- [gomodule](https://github.com/hyper-mcp-rs/gomodule-plugin): Get Go modules info, version (Rust)
- [qdrant](https://github.com/hyper-mcp-rs/qdrant-plugin): keeping & retrieving memories to Qdrant vector search engine (Rust)
- [gitlab](https://github.com/hyper-mcp-rs/gitlab-plugin): GitLab plugin (Rust)
- [meme_generator](https://github.com/hyper-mcp-rs/meme-generator-plugin): Meme generator (Rust)
- [think](https://github.com/hyper-mcp-rs/think-plugin): Think tool(Rust)
- [maven](https://github.com/hyper-mcp-rs/maven-plugin): Maven plugin (Rust)
- [serper](https://github.com/hyper-mcp-rs/serper-plugin): Serper web search plugin (Rust)

### V2 Plugins
These plugins use the v2 plugin interface. New plugins should use this interface.

- [arxiv](https://github.com/hyper-mcp-rs/arxiv-plugin): Search arXiv papers (Rust)
- [context7](https://github.com/hyper-mcp-rs/context7-plugin): Lookup library documentation (Rust)
- [defuddle](https://github.com/hyper-mcp-rs/defuddle-plugin): Get the main content of any page as Markdown (Rust)
- [fetch](https://github.com/hyper-mcp-rs/fetch-plugin): Basic webpage fetching (Rust)
- [monty](https://github.com/hyper-mcp-rs/monty-plugin): A minimal, secure Python interpreter written in Rust for use by AI (Rust)
- [rstime](https://github.com/hyper-mcp-rs/rstime-plugin): Get current time and do time calculations (Rust)
- [sqlite](https://github.com/hyper-mcp-rs/sqlite-plugin): Interact with SQLite (Rust)

### Community-built plugins

- [hackernews](https://github.com/hungran/hyper-mcp-hackernews-tool): This plugin connects to the Hacker News API to fetch the current top stories and display them with their titles, scores, authors, and URLs.
- [release-monitor-id](https://github.com/ntheanh201/hyper-mcp-release-monitor-id-tool): This plugin retrieves project ID from release-monitoring.org, which helps track versions of released software.
- [yahoo-finance](https://github.com/phamngocquy/hyper-mcp-yfinance): This plugin connects to the Yahoo Finance API to provide stock prices (OHLCV) based on a company name or ticker symbol.
- [rand16](https://github.com/dabevlohn/rand16): This plugen generates random 16 bytes buffer and provides it in base64uri format - very usable for symmetric cryptography online.

## Sponsors

Thank you to the organizations that support hyper-mcp. ❤️

<p>
  <a href="https://guidewaycare.com" target="_blank">
    <img src="https://guidewaycare.com/wp-content/uploads/2025/03/guideway-care-logo-2025.svg" alt="Guideway Care" height="60">
  </a>
</p>
