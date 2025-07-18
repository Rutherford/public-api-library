# Comprehensive Library of Free & Publicly Accessible APIs

This list compiles many of the world’s most useful, **free and publicly accessible APIs** across diverse fields.  Each entry summarises what the API provides, whether an API key is required, any stated free usage or rate‑limit information (where available), and links to the official documentation.  Use this as a starting point for building an open API library.

## Government & Socio‑economic Data

| API | What it provides | Free usage & access | Documentation |
|---|---|---|---|
| **NASA APIs** | REST APIs exposing NASA imagery and data (astronomy photos, Mars rover images, Earth observations, planetary information, etc.). The NASA API portal makes NASA data accessible to developers. | Free. A public `DEMO_KEY` exists but signing up for an API key increases rate‑limits. Without a key the default limit is **30 requests/hour** and **50 requests/day**; a registered key raises the daily limit to 1,000 requests. | [api.nasa.gov](https://api.nasa.gov) |
| **U.S. Census Bureau API (ACS & decennial)** | Access to America’s population and economic data.  The API lets developers explore social, economic, housing and demographic statistics from the American Community Survey and Decennial Census. | Free to use; no key required. Rate‑limits are generous but considerate use is encouraged. | [Census API](https://www.census.gov/data/developers.html) |
| **BLS Public Data API** | Provides published historical time‑series data from all Bureau of Labor Statistics surveys (employment, inflation, productivity, etc.).  Results are returned in JSON or Excel. | Free. No registration or API key is required. | [BLS API](https://www.bls.gov/developers/) |
| **FRED/ALFRED API** | RESTful API giving access to over 800,000 economic time series from the Federal Reserve Bank of St. Louis’s FRED and ALFRED databases; outputs XML or JSON. | Free with optional API key. Key increases limit to 120 calls per minute; without a key the limit is 1 call per second. | [fred.stlouisfed.org](https://fred.stlouisfed.org/docs/api/fred/) |
| **api.data.gov** | A free API management service used by U.S. federal agencies; provides a single entry point to more than 450 government APIs. | Free; requires a data.gov API key for some agency APIs but not all. | [api.data.gov](https://api.data.gov/) |
| **NREL Developer Network** | APIs for renewable energy data: building energy efficiency, solar resource, wind, climate, energy optimisation and transportation. | Free. Requires registration for an API key (increases limits). | [developer.nrel.gov](https://developer.nrel.gov/) |
| **World Bank Indicators API** | Access to nearly **16,000** socio‑economic indicators across more than 45 databases (World Development Indicators, International Debt Statistics, Doing Business, etc.).  No authentication is needed. | Free with no key. Rate‑limit unspecified; polite usage encouraged. | [api.worldbank.org](https://api.worldbank.org/) |
| **Eurostat API** | REST APIs (JSON/SDMX) providing EU statistical data and metadata; includes catalogue and statistics services. | Free; no key required. | [ec.europa.eu/eurostat/web/json-and-sdmx-api](https://ec.europa.eu/eurostat/web/json-and-sdmx-api) |
| **FoodData Central API** | USDA API for nutrient and food composition data.  Two endpoints return search results and detailed food data. Anyone may use the API but each request must include a data.gov API key. | Default rate limit is **1,000 requests/hour per IP**; exceeding this temporarily blocks the key. | [fdc.nal.usda.gov/api-guide](https://fdc.nal.usda.gov/api-guide.html) |
| **Open Food Facts API** | Open database of food products contributed by volunteers.  Developers can retrieve ingredients, nutrition facts and other metadata; the database can be reused for any purpose. | Free and open. Current API version is v2; no explicit rate limit but users should read the documentation and abide by fair use. | [openfoodfacts.org](https://openfoodfacts.github.io/openfoodfacts-server/api/) |
| **College Scorecard API** | U.S. Department of Education API providing data on college costs, student debt, graduation rates and post‑graduation earnings. | Requires a free API key. The default rate limit is **1,000 requests per IP per hour**. | [collegescorecard.ed.gov/data/documentation/](https://collegescorecard.ed.gov/data/documentation/) |

## Environment & Earth Science

| API | What it provides | Free usage & access | Documentation |
|---|---|---|---|
| **National Weather Service API (weather.gov)** | Forecasts, alerts, observations and other weather data in JSON‑LD format. | Free, no key required. Rate‑limits exist to prevent abuse. | [weather.gov/documentation/services-web-api](https://www.weather.gov/documentation/services-web-api) |
| **OpenWeatherMap – One Call 3.0** | Minute‑by‑minute, hourly and daily forecasts; government weather alerts; historical weather data. | Free tier allows **1,000 calls/day** (requires API key). | [openweathermap.org/api/one-call-3](https://openweathermap.org/api/one-call-3) |
| **Open‑Meteo** | Open‑source weather API offering high‑resolution forecasts and historical data.  Data is licensed under CC BY 4.0 and available without an API key; free for non‑commercial use. | Up to **10,000 calls/day** before subscription is needed. | [open-meteo.com](https://open-meteo.com/) |
| **USGS Earthquake Catalog API** | Implements the FDSN Event Web Service to search earthquake events by time, location and magnitude. | Free; no key required. Suggests using GeoJSON feeds for real‑time data. | [earthquake.usgs.gov/fdsnws/event/1/](https://earthquake.usgs.gov/fdsnws/event/1/) |
| **OpenAQ API** | Access to global air‑quality data (PM2.5, PM10, SO₂, NO₂, CO, O₃, BC, etc.) in a uniform format; includes near‑real‑time and historical measurements. | Free and open. REST endpoints return JSON; there is no authentication. | [api.openaq.org](https://docs.openaq.org/) |
| **NREL (Renewable energy)** | See Government section above for details – provides renewable energy and climate data. | — | — |

## Finance & Market Data

| API | What it provides | Free usage & access | Documentation |
|---|---|---|---|
| **Alpha Vantage** | Real‑time and historical stock/ETF/mutual fund quotes, forex and crypto rates, economic indicators and 60+ technical indicators. | Free tier with API key; daily limit of 500 requests and 5 calls/minute (higher tiers available). | [alphavantage.co](https://www.alphavantage.co/documentation/) |
| **Marketstack** | Easy‑to‑use REST API for end‑of‑day, intraday and real‑time stock market data covering 30,000+ tickers; offers 15+ years of historical data. | Free plan provides **100 monthly requests**. | [marketstack.com](https://marketstack.com/documentation) |
| **ExchangeRate.host** | Lightweight API for current and historical foreign‑exchange and crypto rates; supports 168 currencies and 19 years of history. | Free plan includes **100 monthly requests** with ~99.99 % uptime. | [exchangerate.host](https://exchangerate.host/) |
| **CoinGecko** | API covering over **3 million** digital assets; provides real‑time prices, trading volume, historical charts, exchange listings, DeFi and NFT data. | Free demo tier allows **30 calls/minute** without an API key; higher tiers available. | [coingecko.com](https://www.coingecko.com/en/api/documentation) |

## Health & Safety

| API | What it provides | Free usage & access | Documentation |
|---|---|---|---|
| **openFDA** | Elasticsearch‑based API returning public data from the FDA (drugs, devices, foods); responses include `meta` and `results` sections.  Datasets include drug adverse events (from 2004 onward). | Requires free API key. Default rate: **240 requests/minute & 1,000 per day** without a key; with a key, **240 requests/minute & 120,000 per day**. HTTPS is required. | [open.fda.gov](https://open.fda.gov/apis/) |
| **WHO Athena API** | Simple query interface to World Health Organization data; URL syntax includes the instance and optional dimension codes.  Output formats include CSV, JSON, XML; an optional `apikey` parameter can be supplied. | Free; token is optional but recommended. | [apps.who.int/gho/athena](https://apps.who.int/gho/athena/api.html) |
| **NCBI E‑utilities** | Programmatic interface to the Entrez system (38 biomedical databases such as PubMed, Gene, Protein). Without an API key, the system allows **3 requests/sec**; with a key, **10 requests/sec**. | API key is free and increases throughput; registration via NCBI account. | [ncbi.nlm.nih.gov/books/NBK25497/](https://www.ncbi.nlm.nih.gov/books/NBK25497/) |

## Education & Research

| API | What it provides | Free usage & access | Documentation |
|---|---|---|---|
| **Crossref REST API** | Open API exposing metadata deposited by Crossref members (bibliographic metadata, funding data, license info, full‑text links, ORCID IDs, abstracts).  Supports search, filters and facets; returns JSON. | Free; no sign‑up required. | [api.crossref.org](https://api.crossref.org) |
| **OpenAlex API** | Access to scholarly works, authors, institutions, venues and concepts.  Free; no authentication.  Daily limit is **100,000 requests per user**. | Include a `mailto` parameter for best performance. | [openalex.org/api](https://docs.openalex.org/api) |
| **GDELT 2.0 API** | Free and open full‑text search across global news articles with a rolling 3‑month window; supports cross‑language search in 65 languages and returns results as JSON/JSONP. | Free; no key required. | [www.gdeltproject.org/api.html](https://www.gdeltproject.org/api.html) |
| **Open Library API** | Provides search, Works and Editions endpoints; Books API returns details by ISBN, OCLC, LCCN or OLID in JSON/YAML. | Free; no key required. | [openlibrary.org/developers/api](https://openlibrary.org/developers/api) |
| **Data USA API** | Allows exploration of the entire Data USA database using query strings; returns JSON responses. | Free; no authentication required. | [datausa.io/about/api/](https://datausa.io/about/api/) |

## Geocoding & Mapping

| API | What it provides | Free usage & access | Documentation |
|---|---|---|---|
| **Nominatim (OpenStreetMap)** | Search and reverse‑geocoding service.  Endpoints `/search`, `/reverse` and `/lookup` find places by name, coordinates or IDs.  Supports free‑form queries and various output formats. | Free, but heavy usage is discouraged.  The OSM Foundation asks users to limit requests to **1 request/sec** and to provide a valid `User‑Agent` header. Unacceptable uses (autocomplete, scraping) may be blocked. | [nominatim.org/release-docs/latest/api/](https://nominatim.org/release-docs/latest/api/) |
| **GeoNames** | REST services for full‑text and postal code search, reverse geocoding, time zones and country information.  Requires a registered `username` parameter; the ‘demo’ account must not be used. | Free for registered users; features include postal code and place name search with results in XML/JSON. | [www.geonames.org/export/web-services.html](https://www.geonames.org/export/web-services.html) |
| **Overpass API** | Read‑only API to query custom subsets of OpenStreetMap data by location, type, tags, etc.; optimized for data consumers needing up to 10 million elements. | Public instances allow up to **10 k queries/day** and **1 GB/day** downloads. | [wiki.openstreetmap.org/wiki/Overpass_API](https://wiki.openstreetmap.org/wiki/Overpass_API) |
| **OpenSky Network** | Real‑time and historical ADS‑B flight data.  Anonymous users can access only the most recent state vectors (10 s resolution) with **400 credits/day**. Registered users can query up to one hour in the past (5 s resolution) with **4,000 credits/day**, while active contributors receive **8,000 credits/day**. | Free. No key required for anonymous access; registration increases limits. | [opensky-network.org/apidoc/](https://opensky-network.org/apidoc/) |
| **Aviationstack** | Real‑time flight status, airline routes and airport data.  The free plan provides **100 requests per month**. | Requires API key. | [aviationstack.com](https://aviationstack.com/documentation) |

## Entertainment, Media & User Content

| API | What it provides | Free usage & access | Documentation |
|---|---|---|---|
| **TMDb (The Movie Database)** | API covering movies, TV shows, actors and images; includes search, discover, and metadata.  Requires registration for an API key; terms of use and rate limits apply. | Free for non‑commercial use; rate‑limits enforced (details in account). | [developer.themoviedb.org](https://developer.themoviedb.org/reference/overview) |
| **OMDb** | RESTful service returning movie information and images contributed by users.  Requests include `apikey=[yourkey]`. | Free keys limited to **1,000 daily requests**. | [omdbapi.com](https://www.omdbapi.com/) |
| **RAWG Video Games Database** | Access to over 500,000 games and millions of screenshots; endpoints include platforms, genres and individual games.  Free personal plan allows **20 k requests/month** and requires attribution. | API key required; commercial plans available. | [rawg.io/apidocs](https://api.rawg.io/docs/) |
| **TheSportsDB** | Free JSON API for sports scores and artwork.  The v1 API uses a numeric key appended to the URL; a test key `123` is available.  Free endpoints include events, players and team details; premium v2 adds live scores. | Free tier; rate‑limits may apply; upgrading unlocks more requests. | [thesportsdb.com/api.php](https://www.thesportsdb.com/api.php) |
| **Last.fm API** | Provides music metadata, artist info and track statistics.  Available to anyone who obtains an API key.  Last.fm enforces rate limits to prevent abuse. | Free for personal use; API key required. | [www.last.fm/api](https://www.last.fm/api) |
| **Spotify Web API** | Access to Spotify’s music catalogue and user data.  To use the API, clients obtain an OAuth access token using the client‑credentials flow and include it in the `Authorization` header.  Spotify enforces a dynamic rate‑limit calculated over a 30‑s window; exceeding the limit returns a 429 error. | Free but requires client ID/secret and OAuth tokens. | [developer.spotify.com](https://developer.spotify.com/documentation/web-api/) |
| **NYTimes Top Stories API** | Returns curated Top Stories articles.  An API key is required; usage is limited to **1,000 requests per day**. | Free for non-commercial use with attribution. | [developer.nytimes.com](https://developer.nytimes.com/docs/top-stories-product/1/overview) |
| **Guardian Open Platform** | Offers access to more than 1.9 million pieces of content.  The *Developer* key (non‑commercial use) allows **1 request/second** and **500 requests/day**; it provides article text and metadata. | Free for non‑profit projects; higher tiers available for commercial use. | [open-platform.theguardian.com](https://open-platform.theguardian.com/) |
| **Random User Generator** | Generates random user profiles for testing.  Returns JSON (default) and supports CSV/YAML/XML.  It was designed as a free, easy‑to‑use service.  You can fetch up to **5,000** users per request. | Free; no API key. | [randomuser.me](https://randomuser.me/documentation) |
| **PokéAPI** | Pokémon database API; provides data on Pokémon species, moves, abilities, locations and more.  It is consumption‑only (HTTP GET) with no authentication; since moving to static hosting in 2018, **rate limits have been removed**, but users are asked to cache results and respect fair use. | Free; no key; abide by fair use policy. | [pokeapi.co](https://pokeapi.co/docs/v2) |
| **Dog API (dog.ceo)** | Collection of open‑source dog images; endpoints return random images or lists by breed.  The project’s about page emphasises that Dog API will remain **free to access and use**. | Free; no key. | [dog.ceo/dog-api/](https://dog.ceo/dog-api/) |

## Corporate & Registry Data

| API | What it provides | Free usage & access | Documentation |
|---|---|---|---|
| **OpenCorporates API** | REST API returning company data in JSON/XML.  Free for open data projects under an open license; API key required; usage limits depend on plan.  A `GET /account_status` endpoint shows daily and monthly usage. | Free for non‑commercial use; register for API key. | [api.opencorporates.com/documentation/API-Reference](https://api.opencorporates.com/documentation/API-Reference) |
| **Companies House API (UK)** | Provides UK company information.  Rate‑limit is **600 requests per 5‑minute window**; exceeding returns HTTP 429.  Higher limits may be available upon request. | Free for users with API key; sign‑up required. | [developer-specs.company-information.service.gov.uk](https://developer-specs.company-information.service.gov.uk/guides/rateLimiting) |

## Flight & Transportation

| API | What it provides | Free usage & access | Documentation |
|---|---|---|---|
| **OpenSky Network** | ADS‑B based flight data.  Anonymous users see only the latest state vectors (10‑s resolution) with **400 credits/day**; registered users get 5‑s resolution and **4,000 credits/day**; active contributors get **8,000 credits/day**. | Free; registration increases limits. | [opensky-network.org/apidoc/](https://opensky-network.org/apidoc/) |
| **Aviationstack** | Global flight status, airline routes and airport data.  Free plan offers **100 requests/month**. | Requires API key. | [aviationstack.com](https://aviationstack.com/documentation) |

## Other Useful APIs

| API | What it provides | Free usage & access | Documentation |
|---|---|---|---|
| **GitHub REST API** | Programmatic access to public GitHub data: repositories, issues, pull requests, user info, etc. Unauthenticated requests are limited to **60 requests/hour**; authenticated users get **5,000 requests/hour**. | Free; personal access token or OAuth increases limits. | [docs.github.com/en/rest](https://docs.github.com/en/rest) |
| **Random User Generator** | See Entertainment section – generates placeholder user data. | — | — |
| **Open Library API** | See Education & Research section. | — | — |
| **NCBI E‑utilities** | See Health & Safety section. | — | — |

## Notes

- **Rate limits**: Many free APIs impose rate limits to prevent abuse.  Always check the latest documentation before production use and cache responses when possible.  Some agencies (e.g., api.data.gov, NCBI, and Companies House) offer higher limits upon request.
- **Authentication**: Some APIs do not require keys (e.g., Nominatim, PokéAPI), while others require free registration.  Use secure storage for API keys and tokens.
- **Data licensing**: Public data often has open licenses (e.g., Open Food Facts, FoodData Central).  Respect attribution requirements and terms of service.

This overview should serve as a foundation for building a website that catalogs free and publicly accessible APIs across multiple domains.  Each entry links to the official documentation for further exploration.
