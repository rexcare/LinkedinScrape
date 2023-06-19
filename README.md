----
Scraper for LinkedIn full profile data. Unlike others scrapers, it's working in 2020 with their new website.

`npm i scrapedin`

### Usage Example:

```javascript
const scrapedin = require('scrapedin')

const profileScraper = await scrapedin({ email: 'login@mail.com', password: 'pass' })
const profile = await profileScraper('https://www.linkedin.com/in/some-profile/')
```

- If you are looking for a crawler to automatically extract multiple profiles see [scrapedin-crawler](https://github.com/linkedtales/scrapedin-linkedin-crawler)
