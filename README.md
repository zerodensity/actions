# Actions

Reusable GitHub Actions workflows for Zero Density's Nodos plugin repositories —
a fork of [nodos-dev/actions](https://github.com/nodos-dev/actions) carrying
Zero Density-specific customizations (private Nodos Store visibility, the
`zerodensitybot` CI user, and a self-contained build matrix).

[`zerodensity/nodos-plugins`](https://github.com/zerodensity/nodos-plugins)
consumes the plugin release workflow via:

```yaml
uses: zerodensity/actions/.github/workflows/plugins.yml@main
```
