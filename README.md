# SwapRadar

Compare crypto swap rates across top no-KYC exchanges instantly.

## What is SwapRadar?

SwapRadar is a single-page web application that compares cryptocurrency swap rates across multiple no-KYC instant exchange services. It helps users find the best rate before swapping, potentially saving 1-2% per trade.

## Exchanges Compared

- **ChangeNOW** - 400+ coins, operating since 2017
- **SimpleSwap** - 600+ coins, operating since 2018
- **Changelly** - 500+ coins, operating since 2015
- **Exolix** - 300+ coins, operating since 2019

## Supported Pairs

- BTC to ETH / ETH to BTC
- BTC to USDT / USDT to BTC
- ETH to USDT
- BTC to XMR
- SOL to USDT
- BTC to LTC

## Tech Stack

- Pure HTML, CSS, JavaScript (zero dependencies, no build step)
- Hosted on GitHub Pages
- Dark theme UI optimized for the crypto audience
- Mobile responsive

## Development

No build tools required. Just open `index.html` in a browser or serve it with any static file server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node
npx serve .
```

## Deployment

The site is deployed automatically via GitHub Pages from the `main` branch.

Live at: https://wagecage.github.io/swapradar/

## Affiliate Setup

Replace `YOUR_REF` in the exchange URLs within `index.html` with your actual affiliate/referral IDs:

- ChangeNOW: `ref=YOUR_REF`
- SimpleSwap: `ref=YOUR_REF`
- Changelly: `ref_id=YOUR_REF`

## License

MIT
