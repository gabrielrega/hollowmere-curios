# Hollowmere Curios

A cozy low-poly fantasy shopkeeping game for mobile browsers, built with three.js.

Aunt Wren left you her curio shop at the crossroads, and a standing debt to the Merchants' Guild. Adventurers come in, take things off your shelves and bring them to the counter.

## How to play

- **Price tags.** Each night, set a tag for every item type. A customer pays a tag that's within their budget, haggles over one a little above it, and puts the item back if it's far above. The Shelves tab keeps notes of recent reactions so you can learn the right price.
- **Haggling.** Your tag is your opening ask. Every counter-offer is below what the customer will really pay, but:
  - each customer has a hidden mood (eager, steady, tight-fisted, proud) that sets their budget, patience and how fast they give ground. You get a tell, which is honest most of the time;
  - a counter-offer only stands for a few seconds. Stall and it gets worse and you lose patience;
  - raising your price above your last ask or your own tag costs double patience.
- **Sellers.** Goblin peddlers and adventurers back from dungeons sell you goods cheaply.
- **Upkeep and tithe.** Rent and candles are due every night and rise slowly. Every seventh night the Guild collects a tithe that grows each week. Three nights in debt and the Guild takes the shop.
- **Events.** Festivals, storms, loot-laden parties and noble retinues change who comes in. Thieves sometimes strike at night; a shop cat helps.
- **Reputation.** Tap the stars to see what each level unlocks and what moves it.
- **Rumors.** Tavern gossip moves tomorrow's demand more than tonight's wholesale prices, and effects fade over several days.
- **Win** the Guild Charter at 2,000 gold.

Progress saves in the browser's local storage each night.

## Running it

It's a single self-contained file. Open `index.html` in a browser, or enable GitHub Pages on this repo (Settings → Pages → deploy from `main`, root) to play it online. three.js r128 loads from cdnjs.
