# dbaratech/homebrew-tap

Homebrew formulae maintained by [@dbaratech](https://github.com/dbaratech).

## Install

```bash
brew install dbaratech/tap/o2cloud
```

or tap first, then install by name:

```bash
brew tap dbaratech/tap
brew install o2cloud
```

## Formulae

- **[o2cloud](https://github.com/dbaratech/o2cloud)** — a scriptable, agent-friendly
  command-line client for O2 Cloud.

> **Note:** the formula installs the base CLI. Browser-assisted login (`o2cloud login`)
> needs the optional Playwright dependency, which is not bundled; install it separately
> (`pip install playwright && playwright install chromium`) or use the manual
> `o2cloud login --import-cookie` flow. See the project README.
