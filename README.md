# onion-api-v1
An API for absurd satire and real headlines.

Spits out a JSON array that contains:
 - Satire The Onion headlines
 - Real 'Not The Onion' headlines

Satire articles are sourced from The Onion's [RSS feed](https://www.theonion.com/rss).  
Real articles are sourced from Reddit: [r/nottheonion/](https://www.reddit.com/r/nottheonion/).

---

Notes:

 * Caches results in `data_cache.json`.
 * Assumes your server timezone is set to UTC for the timestamp, but this otherwise doesn't impact funcitonality at all.
