+++
title = "MC"
subtitle = ""
date = 2021-06-16T12:00:00
lastmod = 2021-06-16T12:00:00
draft = true

authors = ["daniel_antal"]

tags = ["open-data", "open-science", "regional data", "sub-national data", "R", "data collection"]

summary = ""

projects = ["eu-datathon_2021"]

# Featured image
[image]
  # Caption (optional)
  caption = "Annette Wong"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"

  # Show image only in page previews?
  preview_only = true

+++

{{< figure src="/media/img/package_screenshots/regions_017_169.png" numbered="false" >}}

The idea of this observatory was brought to the UK policy debate on music streaming by the observatory’s only (former) British users, via the _Written evidence submitted by The state51 Music Group_ to the _Economics of music streaming review_ of the DCMS Committee (state51 Music Group 2020). The state51 music group was kind not to limit the use of the earlier published dataset for this project.

The music industry requires a permanent market monitoring facility to win fights in competition tribunals, because it is increasingly disputing revenues with the world’s biggest data owners. This was precisely the role of the former CEEMID (Artisjus et al. 2014) program, which was initiated by a group of collective management societies after a dropped GESAC project.

Starting with three relatively data-poor countries, where data pooling allowed rightsholders to increase revenues, the CEEMID data collection program was extended in 2019 to 12 countries. It was eventually transformed to the [Demo Music Observatory](https://music.dataobservatory.eu/) in 2020 (Antal 2021), which is now open for any national rightsholder, stakeholder organization or music research institute.

In April, we started investigating how the music observatory concept could be introduced in the UK, and how our data and analytical skills could be used in the [Music Creators’ Earnings in the Streaming Era](https://digit-research.org/research/related-projects/music-creators-earnings-in-the-streaming-era/) project, which is taking place in a heated political context.

We delivered our preliminary findings to the principal investigators of the project, [Prof David Hesmondhalgh](https://music.dataobservatory.eu/author/prof-david-hesmondhalgh/) and [Dr Hyojugn Sun](https://music.dataobservatory.eu/author/hyojung-sun/) back in April and agreed to make all project data from the final report available in our observatory. 

## Justified and Unjustified Differences in Earnings

Stating that the greatest difference among rightsholders’ earnings is related to the popularity of their works and recorded fixations can appear banal and trivial. Yet, because many payout problems appear in the hard-to-describe long tail, understanding the _justified_ differences of rightsholder earnings is an important step towards identifying the _unjustified_ differences. It would be a breach of copyright law if less popular, or never played artists, would receive significantly more payment at the expense of popular artists from streaming providers. The earnings must reflect the difference in use and the economic value in use among rightsholders.

In our analysis we quantify differences using the actual data of the [CEEMID-CI Streaming Indexes](https://ceereport2020.ceemid.eu/market.html#ceemid-ci-volume-indexes), created from hundreds of millions of data points, and computer simulations under realistic scenarios. 

### Justified Difference & Changes Over Time

Among the _justified_ differences we quantify four objective justifications:

1. _The variability of the domestic price of a stream over time_ show a a diminishing, but variable value of streams. Depending on the release date of a recording, and how quickly it builds up or loses the interest of the audience, the same number of streams can result in about 28% different earnings. In the period 2015-2019, later releases were facing diminishing revenues on streaming platforms. 

2. _The variability of international market share_ and international streaming prices in _International Competitiveness_. Compared to UK streaming prices, most international markets, particularly emerging markets, have a much greater variability of streaming prices. The variability of prices in advanced foreign markets such as Germany was similar to that of the British market, but in emerging markets and smaller advanced markets–such as the Netherlands–we measured a variability of around 50-80%. Artists who have a significant foreign presence, depending on their foreign market share, can experience 2-3 times greater differences in earnings than artists whose audience is predominantly British. 

3. _The variability of the exchange rate_ that is applied when translating foreign currency revenues to the British pound in _Exchange Rate Effects_. Our [CEEMID-CI Streaming Indexes](https://ceereport2020.ceemid.eu/market.html#ceemid-ci-volume-indexes) index covers the post-Brexit referendum period, when the British pound was generally depreciating against most currencies. This resulted in a GBP-denominated translation gain for artists with a foreign presence. We show that the variability of the GBP exchange rates can add _bigger justified differences_ among rightsholders’ earnings than the entire British price variation. The exchange rate movements are typically in the range of 30%, or at the level of the British domestic price variations in streaming prices. In our simulated results, this effect shielded the internationally competitive rightsholders from a significant part of the otherwise negative price change in foreign markets.

4. We were also investigating the choice of _distribution model_. , i.e.,  Both models, the currently used _pro-rata_ model and the _user-centric_ distribution, which has many proponents (and was introduced by SoundCloud in 2021), changes the earnings of artists.   We think that both models represent a bad compromise, but they are legal, and a change of zero-sum distribution change could potentially increase the income of less popular and older artists at the expense of very popular and younger artists. More about this in our forthcoming report!

## Unjustified Differences

In our understanding, there are some known and some hypothetical causes of _unjustified_ earning differences.

1. We did not have systemic data on the _uncollected revenues_–these are earnings that are legally made, but due to documentation, matching, processing, accounting, or other problems, the earnings are not paid. We could not even attempt to estimate this problem in the absence of relevant British empirical data, but our experience in other countries shows that this is a significant problem, and potentially causes great harm to composers, and to smaller labels. Our data curator, [Dr Caterina Sganga](https://music.dataobservatory.eu/author/caterina-sganga/) is working together with us to try to quantify this effect. We are also helping with empirical information a consortium of excellent copyright law researchers to come up with better solutions. 

2. More analysis is required to understand how the algorithmic, highly autonomous recommendation systems of digital platforms such as Spotify, YouTube, Apple, and Deezer, among others, impact music rightsholders’ earnings. There are some empirical findings that suggest that such biases are present in various platforms, but due to the high complexity of recommendation systems, it is impossible to intuitively assign blame to pre-existing user biases, wrong training datasets, improper algorithm design, and other factors (see [Trustworthy AI: Check Where the Machine Learning Algorithm is Learning From](https://dataandlyrics.com/post/2021-06-08-teach-learning-machines/)). Our data curators, [Dr Peter Ormosi](https://music.dataobservatory.eu/author/peter-ormosi/), [Dr Botond Vitos](https://music.dataobservatory.eu/author/botond-vitos/) and [Dominika Semaňáková](https://music.dataobservatory.eu/author/dominika-semanakova/) are working together with us to try to quantify this effect. See our Feasiblity Study to shield Slovak artists from this [here]().

3. There is always a hypothetical possibility that organizations with monopolistic power try to corner the market or make the playing field uneven. The music industry requires a permanent market monitoring facility to win fights in competition tribunals, because it is increasingly disputing revenues with the world’s biggest data owners. (See: [Music Streaming: Is It a Level Playing Field?](https://dataandlyrics.com/publication/music_level_playing_field_2021/).) Our data curator, [Dr Peter Ormosi](https://music.dataobservatory.eu/author/peter-ormosi/) and [Eszter Kabai](https://music.dataobservatory.eu/author/eszter-kabai/) are working together with us to try to quantify this effect.

## Solidarity & Equitable Remuneration

_Equitable remuneration_ is a legal concept which has an economic aspect. In international law, it simply means that men and women should receive equal pay for equal work. Within the context of international copyright law, it was introduced by the Rome Convention, and it means that equitable remuneration means the same payment for the same use, regardless of genre, gender or other unrelated characteristics of the rightsholder.

While the word equitable in everyday usage often implies some level of equality and solidarity, in the context of royalty payments, these terms should not be mixed. 

Solidarity is present in many royalty payout schemes, but it is unrelated to the legal concept of equitable remuneration. Music earnings are very heavily skewed towards a small number of very successful composers, performers, and producers. The music streaming licensing model has little elements of solidarity, unlike some of the licensing models that it is replacing–particularly public performance licensing. However, in those cases, the solidarity element is decided by the rightsholders themselves, and not by external parties like radio broadcasters or streaming service providers. 

The so-called socio-cultural funds that provide assistance for artists in financial need must be managed by rightsholders, not others, and the current streaming model makes the organizations of such solidaristic action particularly difficult.

Our data curator, [Katie Long](https://music.dataobservatory.eu/author/katie-long/) is working on us to find metrics and measurement possibilities on solidarity among rightsolders.


## The Size of the Pie and the Distribution of the Pie

The current debate in the United Kingdom is often organizedaround the submission of the _#BrokenRecord_ campaign to the DCMS committee, which calls for a legal re-definition of equitable remuneration rights (Gray 2020). This idea is not unique to the United Kingdom, in various European jurisdictions, performers fought similar campaigns for legislation or went to court, sometimes successfully, for example, in Hungary. Another hot redistribution topic is the choice between the so-called _pro-rata_ versus _user-centric_ distribution of streaming royalties. 

Our mission with the [Digital Music Observatory](https://music.dataobservatory.eu/) is to help focusing the policy debate with facts around the economics of music streaming.  The legal concept _equitable remuneration_ is inseparable from the economic concept of _fair valuation_, and the music streaming earnings cannot be subject to a valid economic analysis without analyzing _the economics of music_. Streaming services are competing with digital downloads, physical sales, and radio broadcasting; and the media streaming of YouTube and similar services is competing with music streaming, radio, and television broadcasting as well as retransmissions. It is a critically important to determine if in replacing earlier services and sales channels, the new streaming licensing model ( a mix of the mechanical and public performance licensing) is also capable of replacing the revenues for all rightsholders. 

The current streaming licensing model in Europe is a mix of mechanical and public performance rights. Therefore, when we are talking about music streaming, we must compare the streaming sub-market with the digital downloads, physical sales and private copying markets (mechanical licensing), and with the radio, television, cable and satellite retransmission markets (public performance licensing.) Our experience from other countries than the UK tells us that these replacement values are very low. 





We instead propose an alternative approach of _artist-centric distribution_ that could be potentially a win-win for all rightsholder groups; further elaboration of the concept lies outside the scope of this report.



## References

Antal, Daniel. 2021. “Launching Our Demo Music Observatory.” _Data & Lyrics_. Reprex. [https://dataandlyrics.com/post/2020-09-15-music-observatory-launch/](https://dataandlyrics.com/post/2020-09-15-music-observatory-launch/).

Artisjus, HDS, SOZA, and Candole Partners. 2014. “Measuring and Reporting Regional Economic Value Added, National Income and Employment by the Music Industry in a Creative Industries Perspective. Memorandum of Understanding to Create a Regional Music Database to Support Professional National Reporting, Economic Valuation and a Regional Music Study.”

Gray, Tom. 2020. “#BrokenRecord Campaign Submission (Supplementary to Oral Evidence).” UK Parliament website. [https://committees.parliament.uk/writtenevidence/15512/html/](https://committees.parliament.uk/writtenevidence/15512/html/).

state51 Music Group. 2020. “Written Evidence Submitted by The state51 Music Group. Economics of Music Streaming Review. Response to Call for Evidence.” UK Parliament website. [https://committees.parliament.uk/writtenevidence/15422/html/](https://committees.parliament.uk/writtenevidence/15422/html/).

## Join us

*Join our open collaboration Economy Data Observatory team as a [data curator](/authors/curator), [developer](/authors/developer) or [business developer](/authors/team). More interested in environmental impact analysis? Try our [Green Deal Data Observatory](https://greendeal.dataobservatory.eu/#contributors) team! Or your interest lies more in data governance, trustworthy AI and other digital market problems? Check out our [Digital Music Observatory](https://music.dataobservatory.eu/#contributors) team!*

[![Follow GreenDealObs](https://img.shields.io/twitter/follow/EconDataObs.svg?style=social)](https://twitter.com/intent/follow?screen_name=EconDataObs)
