# Contributing

Thanks for helping keep this list accurate. Pull requests that add, fix or remove a newsletter are welcome.

## What gets listed

We list a newsletter when these are all true:

- Its main readers are developers, or people who build software and AI products, such as designers, data teams and engineering managers.
- It sent an issue in the last 90 days, and a public archive or recent issue shows the date. daily.dev Digest is already on the list as an exception, because it has no public archive; don't add further titles on that basis.
- It has a working site where someone can subscribe.
- It goes out by email. Podcasts, blogs without an email edition and social accounts are out of scope.

We remove a newsletter when it has not sent an issue for 90 days, when its site stops working, or when it moves away from developer and AI topics.

## Where to add it

The [README](README.md) is an index of topics and size bands. Each topic has a page under [lists/](lists/), and [lists/largest-developer-newsletters.md](lists/largest-developer-newsletters.md) collects titles with a public audience of 100,000 or more.

Add the newsletter to the right topic page, and to the largest-developer-newsletters page if it belongs there. Sort each table by audience size band (100k+, 25k to 100k, 5k to 25k, under 5k, then unknown), then A to Z by name within the band.

## Entry format

Use one table row:

```
| [Name](https://example.com/) | Who reads it and what it covers, in one plain sentence. | 25k to 100k | Weekly | [Site](https://example.com/) |
```

- Description: one sentence on the readers and the topics. Skip words like "best", "top", "leading" or "must-read".
- Audience size band: 100k+, 25k to 100k, 5k to 25k, under 5k, or unknown. Use a band only when the publisher states a subscriber or reader figure in public, and record that source in the CSV. If there is no public figure, use unknown. Do not estimate a number.
- Frequency: how often it goes out, for example Weekly, Weekdays or Tuesdays and Fridays.
- Link: the newsletter site, or its BuySellAds Discover page if the maintainers have filled that in. Add a sponsor info link only if the newsletter has a public sponsor page.

## Update the data file

Add the same newsletter to [data/newsletters.csv](data/newsletters.csv) with these columns:

| Column | What to put in it |
| --- | --- |
| name | Newsletter name |
| category | Topic name from the README |
| url | Subscribe page or home page |
| discover_url | Leave empty (maintainers fill this in) |
| sponsor_page | Sponsor or advertising page, if public |
| cadence | Same as the Frequency cell |
| audience_public | Publisher's own number, if public, written the way the publisher writes it |
| audience_source | URL where that number appears, or "BuySellAds Discover profile (read YYYY-MM-DD)" when the figure comes from a Discover page |
| subscribers | The same figure as a plain number (for example 25000), or leave empty |
| source_url | The URL of the page that states the figure (for Discover-sourced rows, the Discover page) |
| band | 100k+, 25k to 100k, 5k to 25k, under 5k, or unknown |
| last_issue_date | Date of the most recent issue you found, as YYYY-MM-DD, or YYYY-MM if the only evidence shows the month |
| sells_via_bsa | Leave empty (maintainers fill this in) |
| notes | Anything a reviewer should know, such as where you found the last issue |

## Changing or removing an entry

If you run a newsletter on this list and something is wrong, open a pull request or an issue with the correct details and a link that shows them.

## About the maintainers

BuySellAds maintains this list and sells sponsorships in some of the newsletters on it. Those with a BuySellAds Discover page link to it; the few without one link to their own site, and the CSV marks them. Newsletters do not need to work with BuySellAds to get on the list, and the order is by public size band, then A to Z, never paid.
