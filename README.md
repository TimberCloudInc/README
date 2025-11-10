# TimberCloud

**TimberCloud** is the all-in-one platform built to transform how woodworkers and manufacturers run their business.

We help cabinet shops, millwork houses, door shops, furniture makers, and other production shops sell online, automate quotes, manage orders, track inventory, and streamline production—with tools built specifically for how they actually work (board-foot, square-foot, custom parts, LTL freight, and all the edge cases in between).

This GitHub organization is home to the code, docs, and integrations that power TimberCloud.

---

## 🔩 What We’re Building

Core pillars of the TimberCloud platform:

- **Embedded Storefronts**
  - Embed a modern, branded online store into an existing site.
  - Support for complex, configurable products (dimensions, species, finishes, profiles, hardware, etc.).
  - Customer-specific catalogs, pricing, and rules.

- **Smart Product & Pricing Engine**
  - Custom logic for board-foot, square-foot, linear-foot, unit-based, and assembly-based pricing.
  - Margin controls, minimums, waste factors, upcharges, and project-level overrides.
  - Automatic part breakdowns for production.

- **Orders, Quotes & Workflows**
  - Quote → order → production flows built for real shops.
  - Cut lists, job packets, status tracking, and internal notes in one place.

- **Inventory & Purchasing** (Modular)
  - Track sheets, lumber, hardware, and components across locations.
  - Deduct stock from orders, generate purchase orders, and maintain an audit trail.

- **Shipping & Freight Integrations**
  - Live parcel rates + label generation.
  - LTL & freight workflows for heavy, bulky, made-to-order products.
  - Customer-owned carrier accounts where possible.

- **Developer-Friendly Extensibility**
  - API-first architecture.
  - Hooks for custom business logic, integrations, and automation.

---

## 🏗 Tech Stack (High Level)

- **Backend:** Strapi v4 (Node.js)
- **Frontend:** Next.js + React + Tailwind CSS
- **Payments:** Stripe
- **Data & Infra:** PostgreSQL, Redis, CI/CD pipelines, modern cloud hosting, edge caching
- **APIs & Integrations:** Shipping, freight, tax, and vertical-specific services

Each repository includes its own README with setup and deployment details.

---

## 📁 Repository Overview

Common repositories in this organization:

- `timbercloud-app` — Main web application (Next.js + TimberCloud UI).
- `timbercloud-api` — Strapi backend with custom logic, plugins, and integrations.
- `timbercloud-embed` — Embeddable storefront components and integration SDK.
- `timbercloud-design` — Shared UI components, Tailwind config, and brand assets.
- `timbercloud-integrations-*` — Third-party integrations (shipping, LTL, payments, etc.).
- `timbercloud-docs` — Public documentation, guides, and developer docs.
- `timbercloud-examples` — Example configs, templates, and starter projects.

_Not all repositories are public. Some modules and integrations are private or customer-specific._

---

## 🤝 Contributing

TimberCloud is under active development with a focused internal roadmap.

We currently welcome:

- Bug reports
- Documentation improvements
- Small, self-contained PRs to public packages or examples

**How to contribute:**

1. Open an issue in the relevant public repo.
2. Clearly describe the bug, suggestion, or improvement.
3. We’ll review and respond as we expand our public contribution guidelines.

See `CONTRIBUTING.md` in each repo (where available) for details.

---

## 🧰 For Partners & Integrators

If you are:

- A manufacturing shop interested in TimberCloud,
- A technology partner (shipping, freight, payments, CNC/CAM, etc.),
- An integrator looking to build on top of TimberCloud,

contact us for API access details, sandbox environments, and implementation support.

---

## 📫 Contact

- **Website:** https://timbercloud.com
- **Support:** support@timbercloud.com
- **Sales & Demos:** hello@timbercloud.com

---

## ⚖️ License

Unless otherwise specified in a repository’s `LICENSE` file:

- All rights are reserved by TimberCloud, Inc.
- Some public examples and packages may use a permissive license (e.g. MIT) where explicitly noted.

Always check the `LICENSE` file in each repo before using any code.
