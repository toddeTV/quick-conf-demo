# quick-conf-demo

This repository is a live usage example of the [**Quick Conf Template**](https://github.com/toddeTV/quick-conf).

👉 [https://github.com/toddeTV/quick-conf](https://github.com/toddeTV/quick-conf)

## Purpose

- Show one real conference website setup built with `quick-conf`.
- Provide a practical reference for structure, content modeling, and deployment flow.
- Serve as the source repository for the public demo website.

## Live Demo

- Website: [https://quick-conf.com/](https://quick-conf.com/)
- Source repository: [https://github.com/toddeTV/quick-conf-demo](https://github.com/toddeTV/quick-conf-demo)

## Relation to the Template

The `quick-conf` repository contains the reusable template and update tooling.
This `quick-conf-demo` repository contains one concrete implementation based on that template.

## Run Locally

1. Install dependencies:
   ```bash
   pnpm i --frozen-lockfile --prefer-offline
   ```
1. Start development server:
   ```bash
   pnpm dev
   ```
1. Open the local URL printed in the terminal.

## Content Editing

- Edit content files under `content/` for talks, speakers, sponsors, tickets, FAQ, and pages.
- For browser-based editing, use Nuxt Studio integration and open `/_admin` on the deployed site.
- After saving in Studio, trigger or wait for the deployment pipeline to publish the update.

## Build Commands

- Build: `pnpm build`
- Generate static output: `pnpm generate`
- Run checks: `pnpm test`

## Upstream Template

For template updates, migration guides, and CLI workflow, check:
- [https://github.com/toddeTV/quick-conf](https://github.com/toddeTV/quick-conf)


## License

**Copyright (c) 2025-present, [Thorsten Seyschab](https://todde.tv)**

This repository is a demo implementation based on the Quick Conf template. It is not the template repository itself.

- **Template Source Code (MIT):** The source code originates from the Quick Conf template and follows the template license: [https://github.com/toddeTV/quick-conf/blob/main/LICENSE.md](https://github.com/toddeTV/quick-conf/blob/main/LICENSE.md)

- **Demo Content Data (Restricted):** Content and assets in this demo repository are private and provided for demonstration purposes only.

**Legal Notice & Disclaimer:**

We assume no liability for the use of this project, including all code. You are solely responsible for your use of this project.

For the exact list of restricted files/directories and full license terms, see [LICENSE.md](/LICENSE.md).

### Third-Party Libraries

This project utilizes third-party libraries and other materials. These components are the property of their respective owners and are licensed under their own terms.
