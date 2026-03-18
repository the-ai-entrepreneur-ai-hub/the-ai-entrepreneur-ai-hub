<h1 align="center">George The Developer</h1>
<p align="center">
  <strong>Building production-grade web scrapers & data APIs on <a href="https://apify.com/george.the.developer">Apify</a></strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Apify_Actors-34-blue?style=for-the-badge&logo=apify" alt="34 Actors" />
  <img src="https://img.shields.io/badge/Total_Runs-4,200+-green?style=for-the-badge" alt="4200+ Runs" />
  <img src="https://img.shields.io/badge/Store_Users-300+-orange?style=for-the-badge" alt="300+ Users" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Crawlee-FF6600?style=flat-square&logo=apify&logoColor=white" />
  <img src="https://img.shields.io/badge/Puppeteer-40B5A4?style=flat-square&logo=puppeteer&logoColor=white" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Apify_SDK-0868AC?style=flat-square&logo=apify&logoColor=white" />
</p>

---

## Portfolio Architecture

```mermaid
graph TB
    subgraph PLATFORM["Apify Platform  --  34 Production Actors"]
        direction TB

        subgraph API["Standby APIs  --  Instant Response"]
            E["Email Validator API<br/>$0.002/email"]
            W["Website Intelligence API<br/>$0.005/site"]
            AI["AI Content Detector<br/>$0.003/text"]
            UM["URL Metadata Extractor<br/>$0.003/url"]
            WH["Domain WHOIS Lookup<br/>$0.005/domain"]
            CE["Company Enrichment API<br/>$0.01/company"]
        end

        subgraph SCRAPE["Batch Scrapers  --  High Volume"]
            LI["LinkedIn Employee Scraper<br/>92 users"]
            YT["YouTube Transcript Extractor<br/>73 users"]
            TS["TikTok Shop Scraper<br/>12 users"]
            GS["Google Scholar Scraper"]
            GN["Google News Scraper"]
            TG["Telegram Channel Scraper"]
            TH["Threads by Meta Scraper"]
            RD["Reddit Scraper Pro"]
        end

        subgraph INTEL["Data Intelligence"]
            OF["OFAC Sanctions Screener"]
            OS["Entity OSINT Enricher"]
            SD["Shipping Disruption Tracker"]
            UT["US Tariff Lookup"]
            WC["Website Contact Scraper"]
            CM["CoinMarketCap Scraper"]
        end
    end

    CLIENT(["Your Application"]) -->|REST API| API
    CLIENT -->|Batch Jobs| SCRAPE
    CLIENT -->|Intelligence| INTEL

    style PLATFORM fill:#1a1a2e,stroke:#16213e,color:#fff
    style API fill:#0f3460,stroke:#533483,color:#fff
    style SCRAPE fill:#0f3460,stroke:#533483,color:#fff
    style INTEL fill:#0f3460,stroke:#533483,color:#fff
    style CLIENT fill:#e94560,stroke:#e94560,color:#fff
```

## Top Actors by Adoption

| Actor | Users | Runs | Category |
|-------|------:|-----:|----------|
| [LinkedIn Employee Scraper](https://apify.com/george.the.developer/linkedin-employee-scraper) | 92 | 623+ | Batch Scraper |
| [YouTube Transcript Extractor](https://apify.com/george.the.developer/youtube-transcript-extractor) | 73 | 327+ | Batch Scraper |
| [TikTok Shop Scraper](https://apify.com/george.the.developer/tiktok-shop-scraper) | 12 | 294+ | Batch Scraper |
| [Google News Scraper](https://apify.com/george.the.developer/google-news-scraper) | 4 | - | Batch Scraper |
| [Email Validator API](https://apify.com/george.the.developer/email-validator-api) | - | 200+ | Standby API |
| [CoinMarketCap Scraper](https://apify.com/george.the.developer/coinmarketcap-scraper) | - | 239+ | Data Intel |

## Standby APIs (Instant, Pay-Per-Event)

These actors run as always-on HTTP endpoints -- send a request, get data back in milliseconds:

- **[Email Validator API](https://apify.com/george.the.developer/email-validator-api)** -- MX, SMTP, disposable detection -- `$0.002/email`
- **[Website Intelligence API](https://apify.com/george.the.developer/website-intelligence-api)** -- Tech stack, DNS, SSL, performance -- `$0.005/site`
- **[AI Content Detector](https://apify.com/george.the.developer/ai-content-detector)** -- GPT/AI text detection -- `$0.003/text`
- **[URL Metadata Extractor](https://apify.com/george.the.developer/url-metadata-extractor)** -- Title, OG tags, screenshots -- `$0.003/url`
- **[Domain WHOIS Lookup](https://apify.com/george.the.developer/domain-whois-lookup)** -- Registration, expiry, nameservers -- `$0.005/domain`
- **[Company Enrichment API](https://apify.com/george.the.developer/company-enrichment-api)** -- Firmographics from company name -- `$0.01/company`

## What I Build

I specialize in **production-grade web scrapers and data APIs** that handle anti-bot protections, scale to millions of pages, and deliver clean structured data. Every actor includes:

- Automatic retries and proxy rotation
- Structured JSON/CSV output
- Pay-per-result pricing (you only pay for successful extractions)
- Full API access via Apify platform or direct HTTP

## Tech Stack

```
Runtime:     Node.js 22 + ESM modules
Frameworks:  Crawlee, Apify SDK
Browsers:    Puppeteer, Playwright
Languages:   JavaScript, Python
APIs:        REST, Standby (always-on HTTP)
Platform:    Apify Cloud
```

## Work With Me

Building a scraper, data pipeline, or automation? I deliver production-ready solutions:

- **Custom scrapers** for any website
- **Data APIs** with instant response times
- **Lead generation** pipelines
- **Market intelligence** dashboards

<p align="center">
  <a href="https://apify.com/george.the.developer"><img src="https://img.shields.io/badge/Apify_Store-Browse_All_Actors-blue?style=for-the-badge&logo=apify" /></a>
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=the-ai-entrepreneur-ai-hub&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
</p>
