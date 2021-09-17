# ![redneck](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/tpoc-32x32.png) | redneck (pre-_α_)


## Table of contents

* [**Introduction**](#Introduction)
* [**Opening bids**](#Opening_bids)
  * [_**1-level opening bids**_](#1-level_opening_bids)
    * [1NT opening](#1NT_opening)
      * [_Responses to 1NT opening_](#Responses_to_1NT_opening)
    * [1S opening](#1S_opening)
    * [1H opening](#1H_opening)
    * [1D opening](#1D_opening)
      * [_Relay response to 1D opening_](#Relay_response_to_1D_opening)
      * [_Other responses to 1D opening_](#Other_responses_to_1D_opening)
    * [1C opening](#1C_opening)
      * [_Negative response to 1C opening_](#Negative_response_to_1C_opening)
      * [_Positive response to 1C opening_](#Positive_response_to_1C_opening)

# <a name="Introduction"> Introduction

Redneck is an experimental Bridge bidding system invented by Jack and Neph after one bottle of wine too many.

It has the following notable features:

- All balanced (4333, 4432, and 5332) hands with 10-19 HCP can be shown - divided into four separate HCP ranges - at the 1-level (assuming no interference).
- All unbalanced hands with ca. 11-19 HCP and containing at least one 4-card or longer major suit are opened [1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png)](#1S_opening) or [1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png)](#1H_opening), even if they have a longer minor suit.
- All unbalanced hands with ca. 11-19 HCP and without a 4-card or longer major suit are opened [1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png)](#1C_opening).

1-level openings bids are as follows (where g12 means "good 12" and b12 means "bad 12"):

- [1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png)](#1NT_opening) shows a balanced hand with g12-14 HCP. This bid is not forcing.
- [1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png)](#1S_opening) shows an unbalanced hand (or 5332) with ca. 11-19 HCP and with 4+ spades and fewer than 4 hearts. It might have a longer (or equal length) minor suit. This bid is not forcing.
- [1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png)](#1H_opening) shows an unbalanced hand (or 5332) with ca. 11-19 HCP and with 4+ hearts. It might have a longer (or equal length) spade suit or a longer (or equal length) minor suit. This bid is not forcing.
- [1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png)](#1D_opening) shows a balanced hand with either 10-b12 HCP or 15-17 HCP. This bid is forcing (with one exception).
- [1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png)](#1C_opening) shows either an unbalanced hand with ca. 11-19 HCP and without a 4-card or longer major - or a balanced hand with 18-19 HCP. This bid is forcing.

# <a name="Opening_bids"> Opening bids

## <a name="1-level_opening_bids"> 1-level opening bids

### <a name="1NT_opening"> 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) opening

All balanced (4333, 4432, and 5332) hands with g12-14 HCP (where g12 means "good 12") should be opened 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) - except that a 5332 hand with a 5-card major can be opened [1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png)](#1S_opening) or [1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png)](#1H_opening) if it does not feel "no-trumpy", e.g. if values are concentrated in the major.

A 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) opening bid is not forcing.

#### Some examples

A balanced hand with 13 HCP and scattered honours that should be opened 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)84![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)AQJ6![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)J932![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)KQ7 -- balanced (_2_=_**4**_=_**4**_=3) | 13 HCP

A balanced hand with a "good" 12 HCP - decent 5-card suit with good intermediates and 2 quick tricks  - that should be opened 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)A9![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)J84![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)QT2![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)AJT97 -- balanced (_2_=3=3=**5**) | 12 HCP

A balanced hand with a "bad" 12 HCP - 4333 and "quacky" with poor intermediates and only 1 quick trick - that should be opened [1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png)](#1D_opening) instead:

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)QJ2![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)J82![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)QJ63![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)KQ5 -- balanced (3=3=_**4**_=3) | 12 HCP

A balanced hand with 14 HCP and a 5-card major that should be opened 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)AT![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)QJ763![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)AT2![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)K98 -- balanced (_2_=**5**=3=3) | 14 HCP

A balanced hand with 12 HCP and values concentrated in the 5-card major that could be opened [1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png)](#1S_opening):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)AKQJ9![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)43![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)J62![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)J76 -- balanced (**5**=_2_=3=3) | 12 HCP

#### <a name="Responses_to_1NT_opening"> Responses to 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) opening

These are all fairly standard: Stayman; transfers; quantitative; and so on.

_Details to follow..._

### <a name="1S_opening"> 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) opening

_Coming soon..._

### <a name="1H_opening"> 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) opening

_Coming soon..._

### <a name="1D_opening"> 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening

All balanced (4333, 4432, and 5332) hands with either 10-b12 HCP (where b12 means "bad 12") or 15-17 HCP should be opened 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) - except that a 5332 hand with 15-17 HCP and a 5-card major can be opened [1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png)](#1S_opening) or [1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png)](#1H_opening) if it does not feel "no-trumpy", e.g. if values are concentrated in the major. (A 5332 hand with 10-b12 HCP and a 5-card major will rarely satisfy the "rule of 20" and should only be opened 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png).)

A 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening bid is forcing, with one exception: if responder has less-than-invitational strength even if partner has a 15-17 HCP hand - ca. 7 HCP or less - and has 5+ diamonds, they can pass.

By partnership agreement, you might decide only to open the 10-b12 HCP hands in some circumstances, e.g. only when non-vulnerable or only at favourable vulnerability.

#### Some examples

A balanced hand with 10 HCP that should be opened 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)A7![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)QJ5![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)J9872![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)Q54 -- balanced (_2_=3=**5**=3) | 10 HCP

A balanced hand with 16 HCP that should be opened 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)A974![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)Q9![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)AK87![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)Q43 -- balanced (_**4**_=_2_=_**4**_=3) | 15 HCP

#### <a name="Relay_response_to_1D_opening"> Relay response to 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening

_Details to follow..._

#### <a name="Other_responses_to_1D_opening"> Other responses to 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening

_Details to follow..._


### <a name="1C_opening"> 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) opening

All unbalanced hands with ca. 11-19 HCP and without a 4-card or longer major suit - and all balanced (4333, 4432, and 5332) hands with 18-19 HCP - are opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png).

A 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) opening bid is forcing.

#### Some examples

A minimum unbalanced hand with both minors that should be opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)2![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)J87![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)AT83![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)AQT93 -- unbalanced (_1_=3=_**4**_=**5**) | 11 HCP

A better-than-minimum unbalanced hand with long diamonds that should be opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)T62![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)AK![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)AQ65432![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)7 -- very unbalanced (3=_2_=**7**=_1_) | 13 HCP

A strong unbalanced hand with long clubs that should be opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)KQ3![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)8![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)Q43![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)AKQ842 -- unbalanced (3=_1_=3=**6**) | 16 HCP

A balanced hand with 18 HCP that should be opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)A765![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)KQ2![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)QJ65![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)AQ -- balanced (_**4**_=3=_**4**_=_2_) | 18 HCP

#### <a name="Negative_response_to_1C_opening"> Negative response to 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) opening

_Details to follow..._

#### <a name="Positive_response_to_1C_opening"> Positive response to 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) opening

_Details to follow..._
