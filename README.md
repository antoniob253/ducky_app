# Ducky

Your swim-day companion for Austrian lakes. Ducky combines live weather, water temperature, and official water quality into a single **SwimScore** (0–10) so you know instantly whether it's worth jumping in.

[Download on the App Store](https://apps.apple.com/at/app/ducky/id6760419989)

## Features

- **SwimScore** — one number tells you if conditions are right
- **260+ lakes** — every official Austrian bathing water (AGES data)
- **Live weather** per lake from Open-Meteo
- **Map, list, favourites** — discover nearby or stick to your usual spots
- **"Ich war hier"** — visit tracking with date and weather snapshot
- **Notes** — private per-lake notes for parking, tips, or favourite spots
- **Honest data** — outside swim season, Ducky says so instead of showing stale numbers

## Stack

Swift · SwiftUI · SwiftData · MapKit · CoreLocation · StoreKit 2 · [RevenueCat](https://www.revenuecat.com)

## Data Sources

| Source | Provides |
|--------|----------|
| [AGES](https://www.ages.at) | Water quality, bacteria levels, visibility |
| [Open-Meteo](https://open-meteo.com) | Per-lake weather |
| Apple Maps | Location search, routing |
| Wikipedia | Lake descriptions |

## Running Locally

Open `ducky.xcodeproj` in Xcode 26+ and run on an iOS 26 simulator.

## License

Not open-source. All rights reserved.

## Author

**Antonio Baltic** — [@antoniobaltic](https://github.com/antoniobaltic)
