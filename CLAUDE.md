# Investment Assistant - Claude Code Instructions

## Notion Hub Page
https://www.notion.so/33fcacd2533f81f28e70edda65c9d116

## Notion DB IDs
- Morning Briefing DB: f2823ae6-e16b-4606-ad7c-aa2345cda3b6
- - Watchlist DB: ace8cd77-6ebf-4b0c-bca9-8d056aabdfd3
 
  - ## Core Rules
  - 1. Never list individual stock quantity, avg price, or weight in briefing
    2. 2. Use sector group names only: Semiconductor / Finance / Auto / Healthcare / Energy / Platform
       3. 3. Save numbers to DB properties, analysis text to page body
          4. 4. No duplicate pages for same date - update existing instead
             5. 5. Always save 5 Korean stocks to Watchlist DB as separate pages
               
                6. ## Daily Briefing Flow
                7. 1. Web search: KOSPI, KOSDAQ, S&P500, NASDAQ, USD-KRW, 10Y yield, VIX, WTI
                   2. 2. Read dart_summary.txt for today DART disclosures
                      3. 3. Generate page: summary > market table > analysis > portfolio impact > watchlist > scenarios > schedule > actions
                         4. 4. Watchlist stock priority from DART:
                            5.    - Interim earnings (surprise detection) - highest priority
                                  -    - Treasury buyback - positive signal
                                       -    - Large contract/order - momentum
                                            -    - Dividend declaration - shareholder return
                                                 -    - Rights offering - dilution risk, negative
                                                  
                                                      - ## Weekly Report Flow
                                                      - 1. Web search: weekly market performance
                                                        2. 2. Read dart_weekly_summary.txt for week DART disclosures
                                                           3. 3. Generate: weekly summary > market > sector review > watchlist upgrades > catalysts > rebalancing > action plan
                                                              4. 4. Title: YYYY-WXX weekly portfolio report
                                                                 5. 5. Save to briefing DB
                                                                   
                                                                    6. ## Sector Groups
                                                                    7. - Semiconductor: Samsung(005930), SK Hynix(000660), Hanmi Semi(042700)
                                                                       - - Finance: KB Financial(105560), Hana Financial(086790), JPMorgan(JPM)
                                                                         - - Auto: Hyundai(005380), Kia(000270)
                                                                           - - Healthcare: UnitedHealth(UNH)
                                                                             - - Energy: ExxonMobil(XOM)
                                                                               - - Platform: Alphabet(GOOGL)
