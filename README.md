# NorCal Fleet Summit logo review

A single static page (GitHub Pages) where one invited reviewer rates the twenty-two
logo options 1 to 5 stars, picks favourites and leaves notes, then presses
**Send my review**, which opens a pre-filled GitHub issue in this repo. Results live under Issues.

- No tracking, no network requests, no fonts loaded: logos are inline outlined SVG.
- Progress is kept in the reviewer's own browser (localStorage) until they send.
- `robots.txt` and a `noindex` meta keep it out of search engines.

Built from `review-site-src/review_site.py` in the Fleet Summit Logo folder.
