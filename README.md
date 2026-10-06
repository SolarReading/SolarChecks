# Solar Check Nigeria — v3

This update fixes the solar-results consistency issue.

- Annual generation is the source of truth.
- Daily generation = annual generation / 365.
- Monthly generation = annual generation / 12.
- Effective equivalent hours = daily generation / system kWp.
- Current weather-adjusted output includes orientation losses.
- Existing Nigeria location/LGA data and 50–700 W panel options are retained, including 650 W.

To update GitHub Pages, replace the existing `index.html` with this version and keep `solar-check-hero.png` beside it.
