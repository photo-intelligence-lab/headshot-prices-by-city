# Headshot prices by city (US, 2026-11-12)

**How much does a professional headshot cost in your city?** Open dataset from the **Photo Intelligence Lab by Narkis**:
studio headshot prices for **822 US cities** (out of 1446 cities tracked), collected from photographer
listings and their published session prices. Snapshot date: 2026-11-12.

- US median of city medians: **$321** per headshot session
- 280 cities have 5+ studios listed; every city links to its full photographer list

Interactive version with every city: **[Headshot costs by city study](https://narkis.ai/research/headshot-costs-by-city?utm_source=github&utm_medium=lab-dataset)**
and the **[headshot cost calculator](https://narkis.ai/tools/headshot-cost-calculator?utm_source=github&utm_medium=lab-dataset)** (free embed widget for local sites).

## Headshot prices in the 25 largest US cities

| City | Studios listed | Median price | Typical range (p25-p75) |
|---|---|---|---|
| [New York, New York](https://narkis.ai/headshot-photographers/us/new-york/new-york) | 30 | $495 | $306-$631 |
| [Los Angeles, California](https://narkis.ai/headshot-photographers/us/california/los-angeles) | 13 | $625 | $436-$900 |
| [Chicago, Illinois](https://narkis.ai/headshot-photographers/us/illinois/chicago) | 14 | $350 | $225-$500 |
| [Houston, Texas](https://narkis.ai/headshot-photographers/us/texas/houston) | 14 | $350 | $212-$475 |
| [Phoenix, Arizona](https://narkis.ai/headshot-photographers/us/arizona/phoenix) | 7 | $342 | $250-$412 |
| [Philadelphia, Pennsylvania](https://narkis.ai/headshot-photographers/us/pennsylvania/philadelphia) | 11 | $362 | $288-$456 |
| [San Antonio, Texas](https://narkis.ai/headshot-photographers/us/texas/san-antonio) | 14 | $250 | $175-$312 |
| [San Diego, California](https://narkis.ai/headshot-photographers/us/california/san-diego) | 8 | $350 | $285-$500 |
| [Dallas, Texas](https://narkis.ai/headshot-photographers/us/texas/dallas) | 10 | $338 | $238-$412 |
| [Jacksonville, Florida](https://narkis.ai/headshot-photographers/us/florida/jacksonville) | 9 | $312 | $200-$400 |
| [Fort Worth, Texas](https://narkis.ai/headshot-photographers/us/texas/fort-worth) | 4 | $195 | $195-$195 |
| [San Jose, California](https://narkis.ai/headshot-photographers/us/california/san-jose) | 3 | $500 | $325-$671 |
| [Austin, Texas](https://narkis.ai/headshot-photographers/us/texas/austin) | 12 | $395 | $200-$606 |
| [Columbus, Ohio](https://narkis.ai/headshot-photographers/us/ohio/columbus) | 6 | $350 | $250-$950 |
| [Charlotte, North Carolina](https://narkis.ai/headshot-photographers/us/north-carolina/charlotte) | 9 | $325 | $250-$431 |
| [Indianapolis, Indiana](https://narkis.ai/headshot-photographers/us/indiana/indianapolis) | 9 | $250 | $190-$300 |
| [San Francisco, California](https://narkis.ai/headshot-photographers/us/california/san-francisco) | 9 | $600 | $424-$738 |
| [Seattle, Washington](https://narkis.ai/headshot-photographers/us/washington/seattle) | 12 | $500 | $356-$593 |
| [Denver, Colorado](https://narkis.ai/headshot-photographers/us/colorado/denver) | 15 | $348 | $288-$496 |
| [Washington, District of Columbia](https://narkis.ai/headshot-photographers/us/district-of-columbia/washington) | 11 | $495 | $375-$600 |
| [Nashville, Tennessee](https://narkis.ai/headshot-photographers/us/tennessee/nashville) | 10 | $300 | $244-$400 |
| [El Paso, Texas](https://narkis.ai/headshot-photographers/us/texas/el-paso) | 4 | $150 | $150-$150 |
| [Boston, Massachusetts](https://narkis.ai/headshot-photographers/us/massachusetts/boston) | 7 | $438 | $312-$536 |
| [Portland, Oregon](https://narkis.ai/headshot-photographers/us/oregon/portland) | 10 | $338 | $262-$706 |
| [Detroit, Michigan](https://narkis.ai/headshot-photographers/us/michigan/detroit) | 6 | $300 | $256-$338 |

## By state (median of city medians, states with 5+ priced cities)

| State | Median | Cities |
|---|---|---|
| New Jersey | $750 | 21 |
| Kentucky | $600 | 9 |
| North Dakota | $556 | 6 |
| Wisconsin | $499 | 13 |
| Washington | $432 | 28 |
| Connecticut | $400 | 11 |
| Massachusetts | $400 | 25 |
| New York | $398 | 18 |
| South Carolina | $375 | 15 |
| Mississippi | $369 | 6 |
| Colorado | $362 | 16 |
| Arkansas | $340 | 7 |
| Indiana | $338 | 22 |
| Idaho | $325 | 9 |
| Utah | $325 | 23 |
| Ohio | $324 | 26 |
| Missouri | $319 | 9 |
| Texas | $319 | 68 |
| Virginia | $316 | 12 |
| California | $305 | 121 |
| Louisiana | $302 | 8 |
| Alabama | $300 | 17 |
| Florida | $300 | 68 |
| Minnesota | $300 | 21 |
| Tennessee | $300 | 15 |
| Georgia | $298 | 18 |
| Illinois | $295 | 36 |
| Maryland | $294 | 10 |
| North Carolina | $292 | 26 |
| Arizona | $290 | 21 |
| Pennsylvania | $281 | 14 |
| Oregon | $274 | 16 |
| Oklahoma | $238 | 9 |
| Kansas | $228 | 12 |
| Michigan | $208 | 15 |
| Iowa | $200 | 9 |
| Rhode Island | $200 | 5 |

## Files

`data/headshot_prices_by_city.csv`, one row per city:

| Column | Meaning |
|---|---|
| city, state | US city and state |
| studios_listed | photographers/studios listed for the city in the Narkis directory |
| price_p25_usd, price_p75_usd | typical range: 25th-75th percentile of published session prices |
| price_median_usd | median published session price |
| price_min_usd, price_max_usd | cheapest and most expensive published price |
| population | city population |
| narkis_city_page | the city's photographer page with every listed studio |

Empty price cells = studios exist but none publishes a price.

## Method

Prices are the starting session prices that studios publish on their own sites, gathered for the Narkis headshot
photographer directory. Median and range come from the same per-city studio list (p25-p75), so the median always
sits inside the range. Studio prices change slowly; the snapshot date above is when the table was built. Cities
with few studios are noisy: filter on `studios_listed` before comparing.

## The cheaper option

A studio session costs $321 at the US median for a handful of edited shots. [Narkis](https://narkis.ai?utm_source=github&utm_medium=lab-dataset) trains
an AI model on 15-20 of your selfies and generates up to 200 professional headshots from **$27**, in minutes.
Disclosure: the Photo Intelligence Lab is run by Narkis.

## License

CC BY 4.0. Cite as: *Photo Intelligence Lab by Narkis, "Headshot prices by city", 2026-11-12, https://narkis.ai/research/headshot-costs-by-city*.
