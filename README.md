<h1 align="center">George Kioko</h1>
<p align="center">
  <strong>API Builder & Web Scraping Specialist from Nairobi, Kenya</strong><br/>
  <em>45+ production data APIs on <a href="https://apify.com/george.the.developer">Apify Store</a> | 10K+ runs | 500+ users</em>
</p>

<p align="center">
  <a href="https://apify.com/george.the.developer"><img src="https://img.shields.io/badge/Apify_Store-45+_APIs-blue?style=for-the-badge&logo=apify" alt="45+ APIs" /></a>
  <img src="https://img.shields.io/badge/Total_Runs-10,000+-green?style=for-the-badge" alt="10K+ Runs" />
  <img src="https://img.shields.io/badge/Store_Users-500+-orange?style=for-the-badge" alt="500+ Users" />
</p>

<p align="center">
  <a href="https://x.com/ai_in_it"><img src="https://img.shields.io/badge/X-@ai__in__it-000?style=flat-square&logo=x&logoColor=white" /></a>
  <a href="https://apify.com/george.the.developer"><img src="https://img.shields.io/badge/Apify-george.the.developer-0868AC?style=flat-square&logo=apify&logoColor=white" /></a>
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

## What I Build

I build **production-grade web scrapers and data APIs** that handle anti-bot protections, scale to millions of pages, and return clean structured data. I've shipped 45+ actors on the Apify Store used by hundreds of developers and businesses worldwide.

Every tool I build includes automatic retries, proxy rotation, structured JSON/CSV output, and pay-per-result pricing -- you only pay for successful extractions.

---

## Portfolio Architecture

```mermaid
graph TB
    subgraph PLATFORM["Apify Platform -- 45+ Production Actors"]
        direction TB

        subgraph API["Standby APIs -- Instant Response"]
            E["Email Validator<br/>$0.002/email"]
            W["Website Intelligence<br/>$0.005/site"]
            AI["AI Content Detector<br/>$0.003/text"]
            UM["URL Metadata Extractor<br/>$0.003/url"]
            WH["Domain WHOIS Lookup<br/>$0.005/domain"]
            CE["Company Enrichment<br/>$0.01/company"]
            HU["AI Text Humanizer<br/>$0.003/text"]
        end

        subgraph SCRAPE["Batch Scrapers -- High Volume"]
            LI["LinkedIn Employee Scraper<br/>37 users"]
            YT["YouTube Transcript<br/>40 users"]
            TS["TikTok Shop Scraper"]
            GS["Google Scholar Scraper"]
            GN["Google News Scraper"]
            TG["Telegram Channel Scraper"]
            TH["Threads by Meta Scraper"]
            RD["Reddit Scraper Pro"]
            BL["Bluesky Scraper"]
            PD["PDF Data Extractor"]
            IN["Indeed Jobs Scraper"]
        end

        subgraph INTEL["Data Intelligence"]
            OF["OFAC Sanctions Screener"]
            OS["Entity OSINT Enricher"]
            SD["Shipping Disruption Tracker"]
            UT["US Tariff Lookup"]
            WC["Website Contact Scraper"]
            CM["CoinMarketCap Scraper"]
            DF["Deepfake Detector"]
            SA["Sanctions Checker"]
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

## Top Actors

| Actor | Users | Category |
|-------|------:|----------|
| [LinkedIn Employee Scraper](https://apify.com/george.the.developer/linkedin-employee-scraper) | 37 | Batch Scraper |
| [YouTube Transcript Extractor](https://apify.com/george.the.developer/youtube-transcript-extractor) | 40 | Batch Scraper |
| [Google News Scraper](https://apify.com/george.the.developer/google-news-scraper) | 4 | Batch Scraper |
| [Email Validator API](https://apify.com/george.the.developer/email-validator-api) | -- | Standby API |
| [AI Content Detector](https://apify.com/george.the.developer/ai-content-detector) | -- | Standby API |
| [Google Scholar Scraper](https://apify.com/george.the.developer/google-scholar-scraper) | -- | Batch Scraper |

## Standby APIs (Instant, Pay-Per-Event)

Always-on HTTP endpoints -- send a request, get data back in milliseconds:

- **[Email Validator API](https://apify.com/george.the.developer/email-validator-api)** -- MX, SMTP, disposable detection -- `$0.002/email`
- **[Website Intelligence API](https://apify.com/george.the.developer/website-intelligence-api)** -- Tech stack, DNS, SSL, performance -- `$0.005/site`
- **[AI Content Detector](https://apify.com/george.the.developer/ai-content-detector)** -- GPT/AI text detection -- `$0.003/text`
- **[AI Text Humanizer](https://apify.com/george.the.developer/ai-text-humanizer-api)** -- Rewrite AI text to sound human -- `$0.003/text`
- **[URL Metadata Extractor](https://apify.com/george.the.developer/url-metadata-extractor)** -- Title, OG tags, screenshots -- `$0.003/url`
- **[Domain WHOIS Lookup](https://apify.com/george.the.developer/domain-whois-lookup)** -- Registration, expiry, nameservers -- `$0.005/domain`
- **[Company Enrichment API](https://apify.com/george.the.developer/company-enrichment-api)** -- Firmographics from company name -- `$0.01/company`

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

Need a custom scraper, data pipeline, or automation? I deliver production-ready solutions:

- **Custom scrapers** for any website
- **Data APIs** with instant response times
- **Lead generation** pipelines
- **Market intelligence** dashboards

<p align="center">
  <a href="https://apify.com/george.the.developer"><img src="https://img.shields.io/badge/Apify_Store-Browse_All_APIs-blue?style=for-the-badge&logo=apify" /></a>
  <a href="https://x.com/ai_in_it"><img src="https://img.shields.io/badge/Follow_on_X-@ai__in__it-000?style=for-the-badge&logo=x" /></a>
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=the-ai-entrepreneur-ai-hub&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
</p>
