# Stardew Field Notes

## Background

The [Stardew Valley Wiki](https://stardewvalleywiki.com) is a wonderful resource for anyone playing the game, whether you're playing for the first time or the thousandth.

I find myself visiting the site practically every time I play--what do I use the Stardew Valley Wiki for the most?

- Looking up an item and continually referring to its details
- Looking up a person(s) and continually referring to their favorite item or schedule
- Looking up what Community Center Bundle items I can obtain given the season, weather, and time of day.

Through this process, I end up with several open tabs that I repeatedly switch between while only referring to a small portion of each page. So while the Stardew Valley Wiki is the best source of information, a more specific UI for players (in-game) day-to-day reference can be built.

### Basic UI/UX

Left pane with item and people (etc?) search with rich results, right pane with "pinned" items for continuous reference

Basic Search:

- Search for specific items or people (etc?)
- Rich results are shown (maybe display preview of most important properties in list), can be selected for full view
- Result cards with all details can be "pinned" so they can be referenced at-a-glance

Community Center Bundle Search:

- Enter the specifics of my day (ex: "sunny summer day")
- Rich results including obtainable Community Center Bundle items are shown
- Result cards with all details can be "pinned" so they can be referenced at-a-glance

Future Ideas:

- Organizational section in pinned area
- History
- ...

## Built With

- This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).
- DB? will start with hardcoded json data from wiki--since things don't often change that will do for a while
- May try https://github.com/cristianbote/goober (css-in-js solution)

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Roadmap

- [ ] Implement search
- [ ] Implement pinning UI
- [ ] Implement Community Center Bundle Search

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.
