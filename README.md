# Personal Health Tracker policies

Public documentation for GKCY's personal project. The site contains an introduction, a Privacy Policy, and Terms of Service. It contains no health records, OAuth credentials, or data-processing application.

The policies describe a project under development: local records and optional owner-selected AI analysis where the data source allows it. They explicitly preserve Oura's API/MCP restrictions. These pages are not a guarantee of Oura approval or legal compliance.

The intended published addresses are:

- https://gkcy.github.io/personal-health-policy/
- https://gkcy.github.io/personal-health-policy/privacy.html
- https://gkcy.github.io/personal-health-policy/terms.html

Only use those addresses after a successful Pages deployment.

Static source is in `dist/`. Publish it to the `gh-pages` branch root using GitHub Pages. There are no dependencies or build steps. For local preview, run `python3 -m http.server 8765 --bind 127.0.0.1 --directory dist`.

Update these documents before the workflow changes. Do not put health data or credentials in this public repository or its issues.
