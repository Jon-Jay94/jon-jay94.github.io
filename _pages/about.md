---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html

jmp:
  title: "Trading Volume and Monetary Policy Surprises"
  abstract: >-
    High-frequency identification of the causal effects of monetary policy relies on measuring monetary policy surprises–changes in interest rate futures prices in narrow windows around FOMC announcements capturing unexpected shifts in market-based interest rate expectations. Constructing these surprises entails two key heuristic choices: the event window and the set of interest rate futures contracts. This paper introduces the Volume-Based Monetary Policy Surprise (VBS), which uses abnormal trading volume to let the market endogenously determine the relevant event windows, set of futures contracts and their loadings in the resulting surprise measure for each announcement. The announcement-specific event windows flexibly capture when prices continue adjusting beyond conventional 30-minute windows and when relevant information is released during press conferences. The announcement-specific loadings naturally shift toward longer-dated contracts when the Federal Reserve relies on forward guidance about future policy. The VBS doubles the estimated impact of monetary policy on Treasury yields and equity markets and has a sizable impact on macroeconomic aggregates.
  draft_url: "/files/jonascamargosjensen_jmp.pdf"
  bibtex: |-
    @techreport{camargosjensen2025vbs,
      title={Trading Volume and Monetary Policy Surprises},
      author={Camargos Jensen, Jonas},
      year={2025}
    }
  presentations: "AFA 2026 - Poster Session, 9th HEC Paris Finance PhD Workshop, Barcelona Summer Forum - Advances in Structural Shock Identification, 3rd PhD Workshop on Money & Finance at Sveriges Riksbank"

paper1:
  title: "Liquidity Facilities: Evidence from High-Frequency Identification"
  abstract: >-
    This paper constructs a novel high-frequency liquidity news surprise to identify the effects of Federal Reserve liquidity facility announcements during the Global Financial Crisis and COVID-19 pandemic. Using local projections, we show that liquidity facility announcements substantially lower long-term Treasury yields, with a one percentage point expansionary surprise reducing 10-year yields by approximately 0.2 percentage points. This effect operates almost entirely through term premia rather than expected future short rates. Inconvenience yields on treasury securities fall substantially and primary dealers increase their relative holdings of Treasuries. Our findings demonstrate that liquidity facilities represent an effective tool which reduces risk premia during financial crises.
  coauthors: "with L. Boneva & S. Weidner"
  draft_url: "/files/bcjw_liquidity_facilities.pdf"
  bibtex: |-
    @techreport{bonevacamargosjensenweidner2025,
      title={Liquidity Facilities: Evidence from High-Frequency Identification},
      author={Boneva, Lena and Camargos Jensen, Jonas and Weidner, Stephanie},
      year={2025}
    }
  presentations: "Lancaster ETM Workshop 2024, ECB"

paper2:
  title: "Trading, Beliefs and Monetary Policy Disagreement"
  coauthors: "with L. Henning & I. Kaminska"
  presentations: "12th Uni York–BoE–BdF Asset Pricing Workshop 2025"

---
<style>
/* Homepage paper typography — hard override */
.page__content .paper .paper__abstract,
.page__content .paper .paper__abstract p {
  font-size: 0.80rem !important;
  line-height: 1.62 !important;
}

.page__content .paper .paper__presentations,
.page__content .paper .paper__presentations p,
.page__content .paper .paper__presentations ul,
.page__content .paper .paper__presentations li {
  font-size: 0.72rem !important;
  line-height: 1.50 !important;
}
</style>

Hi, I'm Jonas Camargos Jensen. I'm a PhD candidate in Financial Economics at the **Frankfurt School of Finance & Management**. 

My research lies in the intersection of **monetary economics and asset pricing**, focusing on how financial markets and central banks interact.

I will be on the academic job market in 2025/2026.

---

## Job Market Paper

{% include paper.html title=page.jmp.title status=page.jmp.status abstract=page.jmp.abstract draft_url=page.jmp.draft_url bibtex=page.jmp.bibtex presentations=page.jmp.presentations expanded=true %}


## Working Papers

{% include paper.html title=page.paper1.title coauthors=page.paper1.coauthors abstract=page.paper1.abstract draft_url=page.paper1.draft_url bibtex=page.paper1.bibtex presentations=page.paper1.presentations expanded=false %}



## Work in Progress

{% include paper.html title=page.paper2.title coauthors=page.paper2.coauthors presentations=page.paper2.presentations expanded=false %}