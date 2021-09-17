# ![redneck](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/tpoc-32x32.png) | redneck (pre-_α_)


## Table of contents

* [**Introduction**](#Introduction)
* [**1 level opening bids**](#1_level_opening_bids)
    * [1NT opening bid](#1NT_opening_bid)
      * [_Responses to 1NT opening bid_](#Responses_to_1NT_opening bid)
    * [1S opening bid](#1S_opening_bid)
    * [1H opening bid](#1H_opening_bid)
    * [1D opening bid](#1D_opening_bid)
    * [1C opening bid](#1C_opening_bid)

# <a name="Introduction"> Introduction

Redneck is an experimental Bridge bidding system invented by Jack and Neph after one bottle of wine too many.

It has the following notable features:

- All balanced (4333, 4432, and 5332) hands with 10-19 HCP can be shown - divided into four separate HCP ranges - at the 1-level (assuming no interference).
- All unbalanced hands with ca. 11-19 HCP and containing at least one 4-card or longer major suit are opened 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) or 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png), even if they have a longer minor suit.
- All unbalanced hands with ca. 11-19 HCP and without a 4-card or longer major suit are opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png).

1-level openings bids are as follows (where g12 means "good 12" and b12 means "bad 12"):

- 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) shows a balanced hand with g12-14 HCP. This bid is not forcing.
- 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) shows an unbalanced hand (or 5332) with ca. 11-19 HCP and with 4+ spades and fewer than 4 hearts. It might have a longer minor suit. This bid is not forcing.
- 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) shows an unbalanced hand (or 5332) with ca. 11-19 HCP and with 4+ hearts. It might have a longer spade suit or a longer minor suit. This bid is not forcing.
- 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) shows a balanced hand with either 10-b12 HCP or 15-17 HCP. This bid is forcing (with one exception).
- 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) shows either an unbalanced hand with ca. 11-19 HCP and without a 4-card or longer major - or a balanced hand with 18-19 HCP. This bid is not forcing.

# <a name="1_level_opening_bids"> 1-level opening bids

### <a name="1NT_opening_bid"> 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) opening bid

All balanced (4333, 4432, and 5332) hands with g12-14 HCP (where g12 means "good 12") should be opened 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) - except that a 5332 hand with a 5-card major can be opened 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) or 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) if it does not feel "no-trumpy" (e.g. if values are concentrated in the major).

#### Some examples

A balanced hand with 13 HCP and scattered honours that should be opened 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)84![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)AQJ6![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)J932![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)KQ7 -- balanced (_2_=_**4**_=_**4**_=3) | 13 HCP

A balanced hand with a "good" 12 HCP () that should be opened 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png):

> TODO-NMB...

A balanced hand with a "bad" 12 HCP - 4333 and "quacky" with poor intermediates and only 1 quick trick - that should be opened <a href="#1D_opening_bid">1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png)</a> instead:

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)QJ2![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)J82![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)QJ63![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)KQ5 -- balanced (3=3=_**4**_=3) | 12 HCP

A balanced hand with 14 HCP and a 5-card major that should be opened 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)AT![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)QJ965![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)AT2![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)K98 -- balanced (_2_=**5**=3=3) | 14 HCP

A balanced hand with 12 HCP and values concentrated in the 5-card major that could be opened <a href="#1S_opening_bid">1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png)</a>:

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)AKQJ9![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)43![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)J62![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)J76 -- balanced (**5**=_2_=3=3) | 12 HCP






#### <a name="Responses_to_1NT_opening bid"> Responses to 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) opening bid

These are all fairly standard: Stayman; transfers; quantitative; and so on.

_Details to follow..._

### <a name="1S_opening_bid"> 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) opening bid

_Coming soon..._


### <a name="1H_opening_bid"> 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) opening bid

_Coming soon..._


### <a name="1D_opening_bid"> 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening bid

_Coming soon..._


### <a name="1C_opening_bid"> 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) opening bid

_Coming soon..._

