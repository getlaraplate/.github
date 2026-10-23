# Laraplate

A modular Laravel platform: CMS, CRM, ERP, MES, Shop, Tickets and AI modules on a shared core, with a
Filament backoffice. Install only the modules you need.

> ⚠️ **Caution**: These projects are a **work in progress**. **Don't use them in production or use them at your own risk**—no guarantees are provided... or better yet, collaborate with me to create the definitive Laravel boilerplate; that's the right place to introduce your ideas. Let me know your ideas...

Created and maintained by [@swolley](https://github.com/swolley).

## Repositories

|  | Repository | What it is | License |
|---|---|---|---|
| <img src="https://raw.githubusercontent.com/getlaraplate/brand/main/logos/blueprint/laraplate.svg" width="32" alt="Laraplate"> | [laraplate](https://github.com/getlaraplate/laraplate) | The application: Laravel backend and Filament backoffice | AGPL-3.0 |
| <img src="https://raw.githubusercontent.com/getlaraplate/brand/main/logos/blueprint/core.svg" width="32" alt="LaraCore"> | [laracore](https://github.com/getlaraplate/laracore) | Users, ACL, settings, CRUD API, search, versioning and shared services | AGPL-3.0 |
| <img src="https://raw.githubusercontent.com/getlaraplate/brand/main/logos/blueprint/cms.svg" width="32" alt="LaraCMS"> | [laracms](https://github.com/getlaraplate/laracms) | Contents, categories, tags, moderated comments, multilingual publishing | AGPL-3.0 |
| <img src="https://raw.githubusercontent.com/getlaraplate/brand/main/logos/blueprint/ai.svg" width="32" alt="LaraAI"> | [laraai](https://github.com/getlaraplate/laraai) | Embeddings, vector search, automatic translation, in-app assistant | AGPL-3.0 |
| <img src="https://raw.githubusercontent.com/getlaraplate/brand/main/logos/blueprint/crm.svg" width="32" alt="LaraCRM"> | [laracrm](https://github.com/getlaraplate/laracrm) | Counterparties, contacts, leads and opportunities | AGPL-3.0 |
| <img src="https://raw.githubusercontent.com/getlaraplate/brand/main/logos/blueprint/erp.svg" width="32" alt="LaraERP"> | [laraerp](https://github.com/getlaraplate/laraerp) | Accounting, sales, purchases, invoicing, inventory, projects | AGPL-3.0 |
| <img src="https://raw.githubusercontent.com/getlaraplate/brand/main/logos/blueprint/mes.svg" width="32" alt="LaraMES"> | [larames](https://github.com/getlaraplate/larames) | Work orders, routings, shop-floor events, traceability, quality | AGPL-3.0 |
| <img src="https://raw.githubusercontent.com/getlaraplate/brand/main/logos/blueprint/sao.svg" width="32" alt="LaraSAO"> | [larasao](https://github.com/getlaraplate/larasao) | Ticketing that correlates code, errors and work | AGPL-3.0 |
| <img src="https://raw.githubusercontent.com/getlaraplate/brand/main/logos/blueprint/shop.svg" width="32" alt="LaraShop"> | [larashop](https://github.com/getlaraplate/larashop) | Online sales channel on CMS content and ERP items | AGPL-3.0 |
| <img src="https://raw.githubusercontent.com/getlaraplate/brand/main/logos/blueprint/edge.svg" width="32" alt="LaraEdge"> | [laraedge](https://github.com/getlaraplate/laraedge) | Go edge agent for machine data | AGPL-3.0 |
| <img src="https://raw.githubusercontent.com/getlaraplate/brand/main/logos/blueprint/edge.svg" width="32" alt="LaraEdge SDK"> | [laraedge-sdk](https://github.com/getlaraplate/laraedge-sdk) | Plugin SDK for the edge agent: protocol, Go SDK, conformance suite | Apache-2.0 |
|  | [whisper-api](https://github.com/getlaraplate/whisper-api), [sentence-transformers-api](https://github.com/getlaraplate/sentence-transformers-api) | Self-hosted AI services used by the AI module | Apache-2.0 |

## Our licensing commitment

Laraplate is **dual licensed**: the **AGPL-3.0 edition** is free for everyone, and a **commercial
license** is available to organisations that cannot accept the AGPL obligations. Same software,
different terms. We commit that:

- **The AGPL edition is the project.** Every release is published under the AGPL at the same time
  and with the same code as any commercial release. No commercial-only features, no delayed open
  source releases.
- **Development happens in the open**, for the community and with its help.
- **Contributions stay open**, always available under the AGPL.
- **The commitment outlives us**: it will be written into our
  Contributor License Agreement, which we are finalising, and bind anyone who takes over the project.

Custom work done for a specific customer under a separate agreement is not part of the open source
projects and is outside this commitment. So are the proprietary products built on top of them (UI
applications, vendor-specific machine connectors built as edge plugins on the Apache-2.0 plugin SDK, importers), which live in their own repositories and use only the
public interfaces of the AGPL projects.

Read more in the [contributing guide](https://github.com/getlaraplate/.github/blob/main/CONTRIBUTING.md).

## Get involved

- Questions and ideas: open an issue in the repository concerned, or write to myentity@inwind.it
- Bugs: open an issue in the repository concerned
- Security issues: never in a public issue, write to myentity@inwind.it
