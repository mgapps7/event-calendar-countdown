# event-calendar-countdown

The website for Event Calendar Countdown, a native iPhone and iPad app for marching band and color
guard competitions: <https://mgapps7.github.io/event-calendar-countdown/>

| Page | Address |
| --- | --- |
| Home | `/` |
| Application Help | `/help/` |
| Support | `/support/` |
| Privacy Policy | `/privacy/` |

Plain HTML and CSS, published by GitHub Pages from the root of `main`. Nothing to build. Run
`python3 -m http.server` here to see it locally.

- Keep it free of scripts, third-party fonts, CDNs, analytics and cookies. Each page has a Content
  Security Policy that allows only this site's own styles and images.
- Light mode uses the app's Daylight colors and dark mode its Field Lights colors. Both are set as
  tokens at the top of `assets/site.css`.
- The App Store listing and the app's Setup screen link to `/support/` and `/privacy/`, so those two
  addresses must not change.
- The Privacy Policy and Support text come from `docs/release/` in the app's own repository. Change
  them there as well.
- Use the app's own words. Name no schedule site or circuit, and show no third-party logos.
