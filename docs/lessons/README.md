# Lessons Learned

Reusable patterns and mistakes extracted from the data-readiness project.

## Architecture & Design

- [Hub Consolidation Over Per-Site Scaffolding](hub-consolidation-over-per-site-scaffolding.md) — why N variants of the same structure belong in one project, not N projects
- [Content-Driven Architecture for Regulatory Frameworks](content-driven-architecture-for-regulatory-frameworks.md) — modeling variation as typed content collections with shared components
- [Prototype One Instance Before Scaling to N](prototype-one-instance-before-scaling-to-n.md) — build SOC 2 end-to-end first, then replicate the pattern

## Framework & Tooling

- [MDX Scoped Styles in Astro](mdx-scoped-styles-in-astro.md) — scoped styles don't reach `<Content />` output; use global CSS
- [Astro Plugin Peer Dependency Pinning](astro-plugin-peer-dependency-pinning.md) — `@astrojs/*` packages version independently; pin explicitly
- [Relative Link Fragility in Multi-Section Sites](relative-link-fragility-in-multi-section-sites.md) — trailing slashes break relative hrefs in templated content

## Deployment

- [GitHub Pages Deployment Configuration](github-pages-deployment-configuration.md) — workflow location, CNAME, and site URL must all agree
