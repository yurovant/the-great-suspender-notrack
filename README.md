# The Great Suspender - Without analytics tracking

Modified version of "The Great Suspender" without analytics tracking and rogue .js files from anonymous developer who is now in control of the GitHub source & web store versions.

#### Read more:
- [New ownership announcement](https://github.com/greatsuspender/thegreatsuspender/issues/1175)
- [New maintainer is probably malicious](https://github.com/greatsuspender/thegreatsuspender/issues/1263)
- [Flagged as malware by Microsoft Edge](https://www.windowscentral.com/great-suspender-extension-now-flagged-malware-edge-has-built-replacement)
- [Reddit forum discussion](https://old.reddit.com/r/HobbyDrama/comments/jouwq7/open_source_development_the_great_suspender_saga/)
- [Medium Article](https://medium.com/nerd-for-tech/malware-in-browser-extensions-3805e8763dd5)

This project is a fork from [v7.1.8 of The Great Suspender](https://github.com/greatsuspender/thegreatsuspender) with all tracking code removed, along with some annoying popups/prompts.

### Build from GitHub

Dependencies: openssl, npm.

Clone the repository and run these commands:
```
npm install
npm run generate-key
npm run build
```

It should say:
```
Done, without errors.
```

### Shoutouts

This package uses the [html2canvas](https://github.com/niklasvh/html2canvas) library written by Niklas von Hertzen.  
It also uses the indexedDb wrapper [db.js](https://github.com/aaronpowell/db.js) written by Aaron Powell.  
Thank you also to [BrowserStack](https://www.browserstack.com) for providing free chrome testing tools.  
Original source from [The Great Suspender v7.1.8](https://github.com/greatsuspender/thegreatsuspender).  
