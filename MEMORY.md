# Project Memory

## 2026-11-01

- Latest user request: standalone IronSource code is removed in all variants. Legacy IronSource sources are skipped before dispatch; IronSource is available only through the matching mediation adapter, where included. Rebuild the SDK binary together with these declarations.
- User-requested Taku dependency versions, including Fancy and BeiZi, were synchronized from the SDK variant lockfile. Device builds passed; Baidu 10.070 lacks simulator support, so full Demo simulator linking remains unavailable.

## 2026-10-25

- Uses Taku only; TopOn is restricted to the standalone Global SDK.
- Dependency declarations are synchronized from the matching SDK variant lockfile. Minimum supported iOS is 15 for the current Xcode 27 build. Source SDK archives and Demo device/simulator build checks passed on 2026-10-25; this does not confirm real ad delivery.
- CocoaPods distribution repository for UNAD cn; SDK sources and packaging script are in `../../UNAD-iOS-old`. Keep dependency declarations consistent with the corresponding SDK variant.
