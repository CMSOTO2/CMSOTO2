## Carlos Soto

Senior product engineer based in Columbus, Ohio. I'm passionate about building great UIs
and making them accessible to every user, whatever device, ability or assistive
technology they bring. For 5+ years I've done that with React, React Native and
TypeScript, shipping customer-facing web and mobile products used by millions of people.

To me a UI isn't done until it works for everyone: **accessibility** (WCAG, keyboard,
screen readers, reduced motion) is built in from the first component, **end-to-end tests**
cover the flows real users take, and **performance** holds up on real phones.

### What I work with

|                        |                                                                                              |
| ---------------------- | -------------------------------------------------------------------------------------------- |
| **Languages**          | TypeScript, JavaScript, C# (.NET), SQL, HTML, CSS / Sass                                     |
| **Frontend & mobile**  | React, React Native, Expo, Next.js, TanStack Start, Tailwind CSS                             |
| **State & data**       | TanStack Query (React Query), Zustand, Context API, GraphQL, REST                            |
| **Backend & platform** | .NET APIs, Node.js, PostgreSQL / Supabase, Cloudflare Workers, Stripe                        |
| **Testing**            | Playwright (E2E, desktop + mobile), Cypress, Jest, React Testing Library, Vitest, BackstopJS |
| **Accessibility**      | WCAG, axe DevTools, semantic HTML, keyboard and screen reader support, reduced motion        |
| **UI engineering**     | Design systems, Storybook, responsive and cross-browser work                                 |
| **AI-assisted dev**    | Claude Code for planning, refactors, code review, and writing E2E test suites                |

### Projects

**[Closewatch](https://github.com/CMSOTO2/close-watch)** · [getclosewatch.com](https://getclosewatch.com)
A live SaaS I designed, built and run alone. Turns a proposal PDF into a tracked link that
shows who opened it, how long they read the pricing page, and whether it was forwarded.
TanStack Start on Cloudflare Workers, Supabase Postgres with row-level security, Stripe
subscriptions, Playwright E2E suites on desktop Chrome, iPhone Safari and Android Chrome,
and axe accessibility checks (WCAG 2.2 AA, light and dark) on every push in CI.

<table>
  <tr>
    <td align="center" width="33%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/closewatch/closewatch-proposal-dashboard-ranked-by-intent-dark.webp">
        <img src="assets/closewatch/closewatch-proposal-dashboard-ranked-by-intent.webp" alt="The Closewatch dashboard: open proposals ranked by an intent score out of 100, each showing time on pricing, readers and opens, with a panel explaining the top score">
      </picture>
      <br><sub>Proposals ranked by intent</sub>
    </td>
    <td align="center" width="33%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/closewatch/closewatch-attention-report-time-per-page-pricing-dark.webp">
        <img src="assets/closewatch/closewatch-attention-report-time-per-page-pricing.webp" alt="A proposal's activity page: intent score, opens, viewers and total time, and a bar per page showing ten minutes spent on the pricing page">
      </picture>
      <br><sub>Time spent on each page</sub>
    </td>
    <td align="center" width="33%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/closewatch/closewatch-forwarded-proposal-new-readers-dark.webp">
        <img src="assets/closewatch/closewatch-forwarded-proposal-new-readers.webp" alt="Recent visits on a proposal: the original recipient plus two new readers marked as forwarded from them, with device, location and whether they printed or downloaded it">
      </picture>
      <br><sub>Forwards show up as new readers</sub>
    </td>
  </tr>
</table>

**[Neon Rush](https://github.com/CMSOTO2/neon-rush)**
A 2.5D endless runner for iOS and Android, built with Expo, React Native Skia and
Reanimated at 60/120 FPS. Accessible by design: text scales with Dynamic Type, touch
targets are at least 44 pt, reduce motion is respected, and gameplay cues keep 3:1
contrast for colour-blind players.

<table>
  <tr>
    <td align="center"><img src="assets/neon-rush/menu.png" width="150" alt="Neon Rush main menu: the neon title over a synthwave city street, daily challenge and mission cards, a Play button and a row of menu tabs"><br><sub>Menu</sub></td>
    <td align="center"><img src="assets/neon-rush/city.png" width="150" alt="Neon City: the runner collecting a trail of coins down a glowing magenta road between neon skyscrapers, with trams ahead"><br><sub>Neon City</sub></td>
    <td align="center"><img src="assets/neon-rush/beach.png" width="150" alt="Sunset Beach: the runner surfing a glowing current at dusk, palm trees and beach huts on the left, sailboats and rocks on the right"><br><sub>Sunset Beach</sub></td>
    <td align="center"><img src="assets/neon-rush/jungle.png" width="150" alt="Neon Jungle: the runner on a stone causeway through a bioluminescent jungle with giant trees, glowing mushrooms and carved wooden obstacles"><br><sub>Neon Jungle</sub></td>
    <td align="center"><img src="assets/neon-rush/mountain.png" width="150" alt="Snowy Mountain: the runner snowboarding a night piste with cyan edges under a full moon and an aurora, past snowy pines and snowcats"><br><sub>Snowy Mountain</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="assets/neon-rush/custom-runners.png" width="150" alt="Customization screen, Runners tab: Blitz equipped with cyan headphones, and a grid of the four runners Nova, Blitz, Juno and Rex"><br><sub>Runners</sub></td>
    <td align="center"><img src="assets/neon-rush/custom-outfits.png" width="150" alt="Customization screen, Outfits tab: Juno in the pink Bubblegum outfit with a red snapback, next to the Classic outfit"><br><sub>Outfits</sub></td>
    <td align="center"><img src="assets/neon-rush/custom-gear.png" width="150" alt="Customization screen, Gear tab: Rex in a red lava outfit wearing a gold crown, with Headphones and Snapback as other options"><br><sub>Gear</sub></td>
    <td align="center"><img src="assets/neon-rush/custom-trails.png" width="150" alt="Customization screen, Trails tab: Nova in the dark Midnight outfit with the Prism trail equipped, alongside Neon Stream and Afterburn"><br><sub>Trails</sub></td>
    <td align="center"><img src="assets/neon-rush/custom-boards.png" width="150" alt="Customization screen, Boards tab: Nova standing on the red Magma hoverboard, with Neon Deck, Circuit and Gold Rush boards to choose from"><br><sub>Boards</sub></td>
  </tr>
</table>

**[Global Development Dashboard](https://github.com/CMSOTO2/global-development-dashboard)** · [live demo](https://global-development-dashboard-production.up.railway.app/)
A full-stack data product for exploring GDP, inflation, life expectancy and poverty by
country. React, TypeScript and Visx charts with a world map, a Fastify + SQLite API, and a
Python / Jupyter data pipeline.

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/global-development-dashboard/timeseries.png" alt="GDP growth from 1990 to 2024 as a multi-line chart for eight countries, with metric tabs, region and income filters, and removable country chips above it"><br><sub>Compare countries over time</sub></td>
    <td align="center" width="33%"><img src="assets/global-development-dashboard/scatter.png" alt="Scatter plot of GDP growth against life expectancy for every country, bubbles sized by poverty rate and coloured by region"><br><sub>GDP vs life expectancy</sub></td>
    <td align="center" width="33%"><img src="assets/global-development-dashboard/map.png" alt="World map shaded by life expectancy in 2022, from 54 years in teal to 84 years in deep magenta, with year and metric selectors"><br><sub>World map by indicator</sub></td>
  </tr>
</table>

### Contact

[LinkedIn](https://www.linkedin.com/in/carlos-m-soto/)
