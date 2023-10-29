<p align="center">
  <a href="https://bun.sh"><img src="https://user-images.githubusercontent.com/709451/182802334-d9c42afe-f35d-4a7b-86ea-9985f73f20c3.png" alt="Logo" height=170></a>
</p>
<h1 align="center">bun-monorepo</h1>

## Description

This repository serves as an example setup for a monorepo using [Bun](https://github.com/bunjs/bun).
Supporting:
- nest.js
- nuxt.js

## Installation

```bash
# Install bun
curl -fsSL https://bun.sh/install | bash # for macOS, Linux, and WSL
# to install a specific version
curl -fsSL https://bun.sh/install | bash -s "bun-v1.0.0"

# Clone the repository
git clone https://github.com/jaypeeig/bun-monorepo.git

# Change into the repository directory
cd bun-monorepo

# Install dependencies
bun install
```

## Usage

This monorepo is structured into two main workspaces: `apps/*` and `packages/*`. Modify and organize your applications and packages accordingly.

## Scripts

- **test**: Execute tests (currently configured to echo an error if no tests are specified).

## Bugs and Issues

Found a bug or have a suggestion? Please open an issue on the [GitHub repository](https://github.com/jaypeeig/bun-monorepo/issues).

## License

This project is licensed under the ISC License - see the [LICENSE.md](LICENSE.md) file for details.

## More Information

Visit the [GitHub repository](https://github.com/jaypeeig/bun-monorepo) for more information and updates.
