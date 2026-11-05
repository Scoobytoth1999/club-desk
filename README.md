# Cranbrook Investing Club Desk

A stock-research practice site for the Cranbrook middle school investing club. Students search a company, read the live price, 52-week range, P/E, sales growth, and headlines, then make and save a Buy/Hold/Sell call.

ETFs get their own page: live price and 52-week range, plus a "Basket Facts" section where students use Google buttons to find what the fund tracks, its top holding, how many companies it holds, and its fee (the free data plan can't see inside funds).

**Live site:** https://scoobytoth1999.github.io/club-desk/

## Quick edits (no coding)

Open `config.js` on GitHub, click the pencil icon, edit, then **Commit changes**. The site updates in about a minute.

- `FINNHUB_KEY`: the stock-data key from finnhub.io
- `VSE_URL`: where the "VSE Game" button goes
- `POPULAR`: the stocks shown on the home page
- `POPULAR_ETFS`: the ETFs shown on the home page

## Files

- `index.html`: the whole app (layout, styles, and code)
- `config.js`: settings you'll want to change

## Notes

- Live data comes from Finnhub (finnhub.io). School filters must allow that site.
- Student picks are saved in each student's browser on that device. Clearing browsing data erases them.
- The data key is visible in the page code. It's a free key, so if it's ever misused, make a new one at finnhub.io and update `config.js`.
- Practice tool for learning, not financial advice.
