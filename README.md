# Awesome Screenshot APIs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of screenshot and website capture APIs for developers.

Need to capture website screenshots programmatically? This list covers APIs, open-source tools, and services for generating screenshots, thumbnails, OG images, and visual testing.

## Contents

- [APIs & Services](#apis--services)
- [Open Source](#open-source)
- [Browser Automation](#browser-automation)
- [Use Cases](#use-cases)
- [Articles & Tutorials](#articles--tutorials)

## APIs & Services

| Service | Free Tier | Pricing | Notes |
|---------|-----------|---------|-------|
| [Allscreenshots](https://allscreenshots.com) | 100 lifetime credits | From $10/mo | Full-page capture, dark mode, ad blocking, PDFs, bulk requests. |
| [GrabShot](https://grabshot.dev) | 25/month | From $9/mo | AI cleanup, OG images, fast. Full-featured REST API. |
| [ScreenshotOne](https://screenshotone.com) | 100/month | From $29/mo | Geo-targeting, blockers, animations. |
| [ApiFlash](https://apiflash.com) | 100/month | From $7/mo | Chrome-based, simple API. |
| [Urlbox](https://urlbox.io) | 7-day trial | From $19/mo | Retina, full-page, dark mode. |
| [ScreenshotAPI.net](https://screenshotapi.net) | 100/month | From $9/mo | Lazy-load, full-page, webhooks. |
| [Screenshotlayer](https://screenshotlayer.com) | 100/month | From $10/mo | Part of APILayer. Simple REST API. |
| [Browshot](https://browshot.com) | 100 free | From $15/mo | Multiple browsers, mobile emulation. |
| [Screenshot Machine](https://screenshotmachine.com) | 100/month | From $5/mo | Thumbnails, full-page, PDFs. |
| [Microlink](https://microlink.io) | 50/day | From $12/mo | Metadata + screenshots, edge-cached. |
| [Stillio](https://stillio.com) | None | From $29/mo | Automated scheduled screenshots. |
| [Thum.io](https://www.thum.io) | Watermarked | From $20/mo | Real-time rendering, simple URL-based. |
| [PagePeeker](https://pagepeeker.com) | Limited | From $9/mo | Thumbnails and previews. |
| [SavePage.io](https://savepage.io) | Limited | Free | Desktop and mobile screenshots. |

## Open Source

- [Puppeteer](https://github.com/puppeteer/puppeteer) - Headless Chrome Node.js API. The foundation most screenshot services are built on.
- [Playwright](https://github.com/microsoft/playwright) - Cross-browser automation by Microsoft. Supports Chromium, Firefox, WebKit.
- [Pageres](https://github.com/sindresorhus/pageres) - Capture screenshots of websites in various resolutions.
- [Capture Website](https://github.com/sindresorhus/capture-website) - Capture screenshots using Puppeteer. Simple API.
- [Manet](https://github.com/vbauer/manet) - Screenshot-as-a-service using SlimerJS or PhantomJS.
- [Screenshot API (self-hosted)](https://github.com/alvarcarto/url-to-pdf-api) - Self-hosted URL to PDF/screenshot service.
- [Webshot](https://github.com/nicam/webshot) - Easy website screenshots using PhantomJS (legacy).

## Browser Automation

- [Selenium](https://www.selenium.dev) - The classic browser automation framework.
- [Cypress](https://www.cypress.io) - End-to-end testing with built-in screenshot capture.
- [Splash](https://github.com/scrapinghub/splash) - Lightweight browser for web scraping with screenshot support.

## Use Cases

### OG Image Generation
Use screenshot APIs to automatically generate Open Graph images from your web pages. Set viewport to 1200x630 and screenshot your page for a perfect preview image.

### Visual Regression Testing
Compare screenshots over time to catch unintended UI changes. Tools like [Percy](https://percy.io) and [Chromatic](https://www.chromatic.com) specialize in this.

### Website Monitoring
Capture periodic screenshots to monitor uptime, content changes, or competitor websites.

### Link Previews
Generate thumbnail previews for URL shorteners, bookmarking apps, or social platforms.

### Documentation
Automatically capture screenshots of your app for docs, changelogs, and tutorials.

## Articles & Tutorials

- [How to Generate OG Images with a Screenshot API](https://grabshot.dev/blog/automate-og-image-generation-screenshot-api/) - Automating social preview images
- [Puppeteer Screenshot Guide](https://pptr.dev/guides/screenshots) - Official Puppeteer docs
- [Capturing Screenshots with Playwright](https://playwright.dev/docs/screenshots) - Official Playwright docs

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.
