# Amex.Trade

[![Netlify Status](https://api.netlify.com/api/v1/badges/111be1fa-b6c7-4210-8693-08897fae0cac/deploy-status)](https://app.netlify.com/sites/amex/deploys)

A simple, no-nonsense link forwarder for amex referrals on /[r/churningcanada](https://www.reddit.com/r/churningcanada/)

A few days ago, I read [this thread](https://www.reddit.com/r/churningcanada/comments/cmku46/generate_sleek_shortened_amexco_links_from_any/) about generating "sleek shortened amex.co links" through bit.ly. In essence, because [amex.co](https://amex.co) points to bit.ly, and bit.ly doesn't discriminate referring domains, you are free to use the same url slug through any forwarding url. Unfortunately, since bit.ly's glory days, it has lost several features, including the ability for you to choose custom URL slugs.

This got me thinking: why isn't there a more simple url forwarder for this use case? During a coffee break, after seeing the domain on sale, I purchased amex.trade and deployed it through [Netlify](https://netlify.com).

### Adding your link to amex.trade

1. [Fork this repo](https://github.com/amextrade/amextrade/fork).
2. Add your username to the bottom of `_redirects` in the correct format. Read about Netlify's Redirect handling [here](https://www.netlify.com/docs/redirects/).
3. Submit a [pull request](https://github.com/amextrade/amextrade/pull/new/master).


After verifying that your link is not a duplicate, I will merge your pr. After Netlify deploys the latest changes, you should be able to see your link at https://amex.trade/YOURUSERNAME/CARDTYPE

### Roadmap
* Reddit Bot to handle authentication/verification
* Suggestions? [Raise an issue](https://github.com/amextrade/amex.trade/issues/new)!

### License
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
