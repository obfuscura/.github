<p align="center">
  <img src="https://obfuscura.com/marketing/images/logo.svg" alt="Obfuscura" width="200" onerror="this.style.display='none'">
</p>

<h1 align="center">Obfuscura</h1>

<p align="center">
  <strong>The Modern PHP Code Protection Platform</strong><br>
  Multi-layer bytecode encoding, built-in license management, and zero server extensions.
</p>

<p align="center">
  <a href="https://obfuscura.com">Website</a> •
  <a href="https://obfuscura.com/documentation">Documentation</a> •
  <a href="https://obfuscura.com/security">Security</a> •
  <a href="https://stats.uptimerobot.com/cl7Ol3BfWd">Status</a>
</p>

---

### Open Source Packages

| Repository | Description | Install |
|---|---|---|
| [loader](https://github.com/obfuscura/loader) | Pure-PHP runtime loader for encoded files | `composer require obfuscura/loader` |
| [php-sdk](https://github.com/obfuscura/php-sdk) | PHP SDK for the Obfuscura REST API | `composer require obfuscura/php-sdk` |
| [github-action](https://github.com/obfuscura/github-action) | GitHub Action to encode PHP files in CI/CD | `uses: obfuscura/github-action@v1` |

### What is Obfuscura?

Obfuscura protects commercial PHP applications with multi-layer bytecode encoding — AST parsing, control-flow flattening, string encryption, dead code injection, and bytecode compilation. Each encoded file is unique, even from identical source, defeating pattern-based attacks.

**Key features:**

- **Bytecode Encoding** — Five-stage protection pipeline with no server extensions required
- **License Management** — Domain locking, activation limits, feature gates, and expiration controls
- **Automated Billing** — Connect Stripe and automate license provisioning on purchase
- **REST API** — Encode files, manage licenses, and automate deployments from any CI/CD pipeline
- **PHP 8.0 – 8.4** — Full support for modern syntax including enums, fibers, and readonly properties

### Security

We take security seriously. See our [security practices](https://obfuscura.com/security) and [security.txt](https://obfuscura.com/.well-known/security.txt) for vulnerability reporting.

### Contact

- **Support:** support@obfuscura.com
- **Security:** security@obfuscura.com
