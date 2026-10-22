# weld-scraper

Weld Scraper archives `.gov` websites for the public record, starting with [weld.gov](https://weld.gov).

## Background

<img alt="notice of hearing preview screenshot" width="500" src="https://github.com/user-attachments/assets/58438cf9-ad21-47d9-ac3d-e58200a0b412" />

The above preview was captured on September 3rd, 2026, but shortly after the public hearing, the notice appears to have been [deleted from the Weld County website](https://www.weld.gov/Legal-and-Public-Notices/Planning-Notices/2026-Planning-Notices/Notice-of-Hearing-USR26-0019):

<img alt="page not found webpage screenshot" width="750" src="https://github.com/user-attachments/assets/e186a23d-6776-43f6-9126-f0e2b75bc5db" />

And the [corresponding Internet Archive](https://web.archive.org/web/20261013/https://www.weld.gov/Legal-and-Public-Notices/Planning-Notices/2026-Planning-Notices/Notice-of-Hearing-USR26-0019) also failed to capture this, showing:

<img alt="not archived screenshot" width="750" src="https://github.com/user-attachments/assets/9dac801d-4f19-44cd-a669-39724b18237e" />

## MVP

The [MVP](https://en.wikipedia.org/wiki/Minimum_viable_product) is weld.gov-archive.org showing:

### 1. https://www.weld.gov/Legal-and-Public-Notices
### 2. all pages under https://www.weld.gov/Legal-and-Public-Notices
### 3. a history / snapshot of above showing any additions, deletions, changes captured at least once a week starting before October 31st, 2026 through September 1st, 2027
### 4. work transparently published under a freedom centered / copy left / open source license

## Stretch Goals

As resources permit:

### a. automatically flag/notify changes that match certain criteria, e.g. a user may request notifications for changes related to water in Weld county
### b. support/maintenance past September 1st, 2027
### c. user submitted feature requests
### d. archiving all of weld.gov and/or additional .gov websites (not just weld.gov)

## Out of Scope

Explicitly we (the owners of weld.gov and developers in this github repo) do not want to do any of the following

* accept any money / make money (we will happily reject any money -- this work is entirely funded by the developers and powered by free / opensource contributions)
* support / endorse any political candidate / position (we support transparency and facts -- we support all political views / opinions in leveraging facts and historical records)
