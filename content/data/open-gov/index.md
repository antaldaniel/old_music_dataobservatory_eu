---
title: Open Government Data
summary: Public-sector information re-use and freedom of information
tags:
- psi
- open-gov
- foi
date: "2021-05-16T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/EconDataObs
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Many countries in the world allow access to a vast array of information,
such as documents under freedom of information requests, statistics,
datasets. In the European Union, most taxpayer financed data in
government administration, transport, or meteorology, for example, can
be usually re-used. More and more scientific output is expected to be
reviewable and reproducible, which implies open access.

In the EU, open data is governed by the [Directive on open data and the re-use of public sector information - in short: Open Data Directive (EU) 2019 / 1024](https://eur-lex.europa.eu/legal-content/EN/TXT/?qid=1561563110433&uri=CELEX:32019L1024). It entered into force on 16 July 2019. It replaces the [Public Sector Information Directive](https://eur-lex.europa.eu/legal-content/en/ALL/?uri=CELEX:32003L0098), also known as the *PSI Directive* which dated from 2003 and was subsequently amended in 2013.

<table>
<tbody>
<tr class="odd">
<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/photo-1490004047268-5259045aa2b4.jpg" caption="[What’s the Problem with Open Data?](/data/open-gov/#open-data-problems)" numbered="false" >}}</td>
<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/photo-1590247813693-5541d1c609fd.jpg" caption="[How We Add Value?](/data/open-gov/#open-data-value-added)" numbered="false" >}}</td>
</tr>
<tr class="even">
<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/photo-1533580909002-a2f298d005eb.jpg" caption="[Is There Value in It?](/data/open-gov/#open-data-problems)" numbered="false" >}}</br>If it’s money on the street, why nobody’s picking it up?</td>
<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/photo-1605143185650-77944b152643.jpg" caption="[Datasets Should Work Together to Give Information](/data/open-gov/#open-data-problems)" numbered="false" >}}</br>If it’s money on the street, why nobody’s picking it up?</td>
</tr>
</tbody>
</table>



## What’s the Problem with Open Data? {#open-data-problems}

If open data is the new gold, why even those who release fail to reuse
it? We created an open collaboration of data curators and open-source
developers to dig into novel open data sources and/or increase the
usability of existing ones. We transform reproducible research software
into research-as-service.

- Most open data cannot be just ["downloaded."](/data/open-gov/)

{{< figure src="/media/img/observatory_screenshots/observatory_collage_16x9_800.png" caption="Our review of about 80 EU, UN and OECD data observatories reveals that most of them do not use these organizations's open data - instead they use various, and often not well processed proprietary sources." numbered="false" >}}

Read more: [Open Data - The New Gold Without the
Rush](https://dataandlyrics.com/post/2021-06-18-gold-without-rush/)

## Is There Value in Open Data? {#is-there-value}

- Open data is often untapped and provides you competitive advantage in scientific research or market intellgience. Most open data is not publicy accessible, and available upon request.
- Most European open data comes from tax authorities, meteorological offices, managers of transport infrastructure, and other governmental bodies whose data needs are very different from yours.  Their data must be carefully evaluated, re-processed, and if necessary, imputed to be usable for your scientific, business or policy goals.
- The use of open science data is problematic in different ways: usually understanding the data documentation requires domain-specific specialist knowledge.  [Open science data](https://music.dataobservatory.eu/data/open-science/) is even more scattered and difficult to access than technically open, but not public governmental data.


## How We Add Value {#open-data-value-added}

[Our team](/#contributors) knows how to bring data to the light, and release it in the best possible format with the highest quality documentation.

-   We believe that even such generally trusted data sources as Eurostat
    often need to be reprocessed, because various legal and political
    constraints do not allow the common European statistical services to
    provide optimal quality data – for example, on the regional and city
    levels.
-   With
    [rOpenGov](https://greendeal.dataobservatory.eu/authors/ropengov/)
    and other partners, we are creating open-source statistical software
    in R to re-process these heterogenous and low-quality data into tidy
    statistical indicators to automatically validate and document it.
-   We are carefully documenting and releasing administrative,
    processing, and descriptive metadata, following international
    metadata standards, to make our data easy to find and easy to use
    for data analysts.
-   We are automatically creating depositions and authoritative copies
    marked with an individual digital object identifier (DOI) to
    maintain data integrity.
-   We are building simple databases and supporting APIs that release
    the data without restrictions, in a tidy format that is easy to join
    with other data, or easy to join into databases, together with
    standardized metadata.
-   We maintain observatory websites (see: \[Digital Music
    Observatory\](<https://music.d> ![Our service flow and value
    chain](https://greendeal.dataobservatory.eu/media/img/slides/automated_observatory_value_chain.jpg "Our service flow and value chain")

Metadata is a potentially informative data record about a potentially
informative dataset.

## Photo Credits

*What’s the Problem with Open Data?* illustration is a photo by
[Cristina Gottardi](https://unsplash.com/photos/8hJQKRIQZMY) 
*How We Add Value?* illustration is a photo by [Nana
Smirnova](https://unsplash.com/photos/IEiAmhXehwE).
** is a photo by [Imelda](https://unsplash.com/photos/GcnPjvqRL18)

## Footnote References

[1] Pomerantz, Jeffrey. 2021. “Metadata.” MIT Press essential knowledge
series. MIT Press. Cambridge, Massachusetts ; London, England : The MIT
Press, \[2015\]

[2] Pomerantz, Jeffrey. 2021. “Metadata.” MIT Press essential knowledge
series. MIT Press. Cambridge, Massachusetts ; London, England : The MIT
Press, \[2015\]




## Why Downloading Does Not Work?

-  Most open data is not available on the internet. 
- If it is available, it is not in a form that you can easily import into a spreadsheet application like Excel or OpenOffice, or into a statistical application like SPSS or STATA.
- Even the data quality of trusted web sources, like the Eurostat website, can be very low. Eurostat just publishes what it gets from governments, and often has no mandate to fix errors.  The data is full with missing information, and in the case of regional statistics, faulty region codes and region names that make matching your data or placing them on a map impossible.
- Adjusting euros with millions of euros, correctly translating dollars to euros, pounds to kilograms requires plenty of work. This is a very error-prone process when done by humans.

## Can Open Data be Used in Machine Learning and AI?

- Most public and open data sources have many missing observations; machine learning models usually cannot hanlde missingness. These points must be carefully imputed with approximations, which can be very challenging when the data has geographical dimension.
- Removing missing values makes samples extremely biased and your model will learn from omissions, not information.

## How We Add Value?



