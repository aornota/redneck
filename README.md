# ![redneck](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/tpoc-32x32.png) | redneck (pre-_α_)

![they took our bids!](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/redneck.jpg)

## Table of contents

* [**Introduction**](#Introduction)
* [**Opening bids**](#Opening_bids)
  * [_**1-level opening bids**_](#1-level_opening_bids)
    * [1NT opening](#1NT_opening)
      * [_Responses to 1NT opening_](#Responses_to_1NT_opening)
      * [_Coping with interference after 1NT opening_](#Coping_with_interference_after_1NT_opening)
    * [1S opening](#1S_opening)
      * [_Responses to 1S opening_](#Responses_to_1S_opening)
      * [_Coping with interference after 1S opening_](#Coping_with_interference_after_1S_opening)
    * [1H opening](#1H_opening)
      * [_Responses to 1H opening_](#Responses_to_1H_opening)
      * [_Coping with interference after 1H opening_](#Coping_with_interference_after_1H_opening)
    * [1D opening](#1D_opening)
      * [_Relay response to 1D opening_](#Relay_response_to_1D_opening)
      * [_Weak transfer responses to 1D opening_](#Weak_transfer_responses_to_1D_opening)
      * [_1NT response to 1D opening_](#1NT_response_to_1D_opening)
      * [_Coping with interference after 1D opening_](#Coping_with_interference_after_1D_opening)
    * [1C opening](#1C_opening)
      * [_Negative response to 1C opening_](#Negative_response_to_1C_opening)
      * [_Positive response to 1C opening_](#Positive_response_to_1C_opening)
      * [_Weak jump responses to 1C opening_](#Weak_jump_responses_to_1C_opening)
      * [_Coping with interference after 1C opening_](#Coping_with_interference_after_1C_opening)

# <a name="Introduction"> Introduction

Redneck is an experimental Bridge bidding system invented by Jack and Neph after one bottle of wine too many.

It has the following notable features:

- All balanced (4333, 4432, and 5332) hands with 10-19 HCP can be shown - divided into four separate HCP ranges - at the 1-level (assuming no interference).
- All unbalanced hands with ca. 11-19 HCP and containing at least one 4-card or longer major suit are opened [1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png)](#1S_opening) or [1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png)](#1H_opening), even if they have a longer (or equal length) minor suit.
- All unbalanced hands with ca. 11-19 HCP and without a 4-card or longer major suit are opened [1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png)](#1C_opening).

Specifically, the 1-level openings bids are as follows (where g12 means "good 12" and b12 means "bad 12"):

- [1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png)](#1NT_opening) shows a balanced hand with g12-14 HCP. This bid is not forcing.
- [1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png)](#1S_opening) shows an unbalanced hand (or occasionally 5332) with ca. 11-19 HCP and with 4+ spades and fewer than 4 hearts. It might have a longer (or equal length) minor suit. This bid is not forcing.
- [1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png)](#1H_opening) shows an unbalanced hand (or occasionally 5332) with ca. 11-19 HCP and with 4+ hearts. It might have a longer (or equal length) spade suit and/or a longer (or equal length) minor suit. This bid is not forcing.
- [1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png)](#1D_opening) shows a balanced hand with either 10-b12 HCP or 15-17 HCP. This bid is forcing (with one exception).
- [1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png)](#1C_opening) shows either an unbalanced hand with ca. 11-19 HCP and without a 4-card or longer major - or a balanced hand with 18-19 HCP. This bid is forcing.

# <a name="Opening_bids"> Opening bids

## <a name="1-level_opening_bids"> 1-level opening bids

### <a name="1NT_opening"> 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) opening

All balanced (4333, 4432, and 5332) hands with g12-14 HCP (where g12 means "good 12") should be opened 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) - except that a 5332 hand with a 5-card major can be opened [1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png)](#1S_opening) or [1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png)](#1H_opening) if it does not feel "no-trumpy", e.g. if values are concentrated in the major.

A 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) opening bid is not forcing.

##### Some examples

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

#### <a name="Coping_with_interference_after_1NT_opening"> Coping with interference after 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) opening

_Coming soon..._

### <a name="1S_opening"> 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) opening

All unbalanced hands (and the occasional 5332 hand) with ca. 11-19 HCP and with 4+ spades and fewer than 4 hearts are opened 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png).

Note that these hands might have a longer (or equal length) minor suit.

A 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) opening bid is not forcing.

##### Some examples

_Coming soon..._

TODO-NMB...Blah blah blah should be opened 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png):

![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)AK63![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)T42![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)-![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)AQJT62 -- very unbalanced (_**4**_=3=_0_=**6**) | 14 HCP

#### <a name="Responses_to_1S_opening"> Responses to 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) opening

_Details to follow..._

#### <a name="Coping_with_interference_after_1S_opening"> Coping with interference after 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) opening

_Coming soon..._

### <a name="1H_opening"> 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) opening

All unbalanced hands (and the occasional 5332 hand) with ca. 11-19 HCP and with 4+ hearts are opened 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png).

Note that these hands might have a longer (or equal length) spade suit and/or a longer (or equal length) minor suit.

A 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) opening bid is not forcing.

##### Some examples

_Coming soon..._

#### <a name="Responses_to_1H_opening"> Responses to 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) opening

_Details to follow..._

#### <a name="Coping_with_interference_after_1H_opening"> Coping with interference after 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) opening

_Coming soon..._

### <a name="1D_opening"> 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening

All balanced (4333, 4432, and 5332) hands with either 10-b12 HCP (where b12 means "bad 12") or 15-17 HCP should be opened 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) - except that a 5332 hand with 15-17 HCP and a 5-card major can be opened [1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png)](#1S_opening) or [1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png)](#1H_opening) if it does not feel "no-trumpy", e.g. if values are concentrated in the major.

(A 5332 hand with 10-b12 HCP and a 5-card major will rarely satisfy the "rule of 20" and should only be opened 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png).)

A 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening bid is forcing, with one exception: when responder has less-than-invitational strength even if opener has a 15-17 HCP hand - ca. 7 HCP or less - with 5+ diamonds, they can pass.

(See [weak transfer responses](#Weak_transfer_responses_to_1D_opening) for when responder has ca. 7 HCP or less and a different 5+ card suit - and [relay response](#Relay_response_to_1D_opening) for when responder has ca. 7 HCP or less and no 5+ card suit.)

By partnership agreement, you might decide only to open the 10-b12 HCP hands in some circumstances, e.g. only when non-vulnerable or only at favourable vulnerability.

##### Some examples

A balanced hand with 10 HCP that should be opened 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)A7![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)QJ5![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)J9872![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)Q54 -- balanced (_2_=3=**5**=3) | 10 HCP

A balanced hand with 16 HCP that should be opened 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)A974![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)Q9![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)AK87![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)QJ3 -- balanced (_**4**_=_2_=_**4**_=3) | 16 HCP

#### <a name="Relay_response_to_1D_opening"> Relay response to 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening

When responder has ca. 8+ HCP - or ca. 7 HCP or less and no 5+ card suit - they should make a relay response of 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png).

If opener has a 10-b12 HCP hand, they should rebid 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png). Responder then rebids as follows:

- With ca. 7 HCP or less and no 5+ card suit, they should bid 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png). Opener must pass.
- With a less-than-invitational hand - ca. 8-b13 HCP - and no 5+ card major (or 6+ card minor) - they should bid 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png). Opener must pass.
    - With a less-than-invitational hand and a 5+ card major, they should transfer - as over a 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) opening bid - and pass opener's forced rebid.
    - With a less-than-invitational hand and a 6+ card minor, they can transfer and pass opener's forced rebid if they feel that 3![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) or 3![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) will be better than 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png).
- Otherwise, responder's rebids are analogous to the [responses to a 1NT opening bid](#Responses_to_1NT_opening) (albeit taking into account that opener's point range is 10-b12 HCP, not g12-14 HCP).

If opener has a 15-17 HCP hand, they should rebid 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png). Responder's rebids are analogous to the [responses to a 1NT opening bid](#Responses_to_1NT_opening) (albeit taking into account that opener's point range is 15-17 HCP, not g12-14 HCP).

#### <a name="Weak_transfer_responses_to_1D_opening"> Weak transfer responses to 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening

When responder has less-than-invitational strength even if opener has a 15-17 HCP hand - ca. 7 HCP or less - and has 5+ cards in a suit other than diamonds, they can make a weak transfer response and then pass opener's forced rebid, as follows:

- With 5+ clubs, they respond 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) and opener is forced to rebid 2![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png).
- With 5+ hearts, they respond 2![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) and opener is forced to rebid 2![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png).
- With 5+ spades, they respond 2![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) and opener is forced to rebid 2![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png).

(Note that with 5+ cards in a major suit, the transfer response is the same as over a 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) opening bid. Although responder could relay with 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) and then transfer, transferring immediately is preferable: relaying would leak information about opener's HCP range - and would also be more vulnerable to interference.)

As mentioned above, with 5+ diamonds, responder can just pass the 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening bid.

##### An example

A less-than-invitational hand with 5+ clubs that should make a weak transfer response of 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png), then pass opener's forced 2![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) rebid:

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)QJ7![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)95![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)742![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)K9852 -- balanced (3=_2_=3=**5**) | 6 HCP

#### <a name="1NT_response_to_1D_opening"> 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) response to 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening

When responder has invitational strength if opener has a 10-b12 HCP hand - ca. g13-14 HCP - and a balanced hand (usually without a 4-card or longer major), they can invite game by responding 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png).

(When responder has a 4-card or longer major, they should generally prefer to relay with 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) and then make a Stayman or transfer bid.)

If opener has a 10-b12 HCP hand, they should rebid 3![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) with a maximum and pass otherwise.

If opener has a 15-17 HCP hand, they should rebid 3![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) (or explore for a thin slam).

##### An example

A balanced hand (without a 4-card or longer major) with invitational strength if opener has a 10-b12 HCP hand that should respond 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)J94![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)AK3![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)KQT2![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)T98 -- balanced (3=3=_**4**_=3) | 13 HCP

#### <a name="Coping_with_interference_after_1D_opening"> Coping with interference after 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) opening

_Coming soon..._

### <a name="1C_opening"> 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) opening

All unbalanced hands with ca. 11-19 HCP and without a 4-card or longer major suit - and all balanced (4333, 4432, and 5332) hands with 18-19 HCP - are opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png).

(As usual, a 5332 hand with 18-19 HCP and a 5-card major can be opened [1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png)](#1S_opening) or [1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png)](#1H_opening) if it does not feel "no-trumpy".)

A 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) opening bid is forcing.

##### Some examples

A minimum unbalanced hand with both minors that should be opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)2![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)J87![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)AT83![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)AQT93 -- unbalanced (_1_=3=_**4**_=**5**) | 11 HCP

A very unbalanced hand with long diamonds that should be opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)T62![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)AK![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)AQ765432![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)- -- very unbalanced (3=_2_=**8**=_0_) | 13 HCP

A strong unbalanced hand with long clubs that should be opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)KQ3![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)8![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)Q43![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)AKQ842 -- unbalanced (3=_1_=3=**6**) | 16 HCP

A balanced hand with 18 HCP that should be opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)A765![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)KQ2![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)QJ65![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)AQ -- balanced (_**4**_=3=_**4**_=_2_) | 18 HCP

#### <a name="Negative_response_to_1C_opening"> Negative response to 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) opening

When responder has a very weak hand - ca. 5 HCP or less - they should usually make a negative response of 1![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png).

(If they have a long suit - ideally 7+ cards - they should prefer a [weak "jump" response](#Weak_jump_responses_to_1C_opening) instead.)

Opener rebids as follows:

- With 5+ diamonds, they pass. (This will occasionally mean playing in a 5- or 6-card diamond fit. Can't win 'em all.)
- With exactly 4 diamonds and 5 clubs, they rebid 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png). (Note that since they would not have opened 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) with a 4-card major, they cannot have a major suit void: with 4=0=4=5 or 0=4=4=5, they would have opened 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) or 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png) respectively.) Responder then rebids as follows:
    - With 6+ hearts (therefore at least a 7-card fit) and no 9-card or longer minor suit fit, they pass.
    - With 6+ spades (therefore at least a 7-card fit) and no 9-card or longer minor suit fit, they bid 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png). Opener must pass.
    - With at least a 7-card fit in one or both minors, they bid the longer fit (i.e. 2![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) or 2![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png)). Opener must pass.
    - Otherwise, they bid 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png). Opener must pass.
- With 6+ clubs, they rebid 2![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png). Responder must pass.

#### <a name="Positive_response_to_1C_opening"> Positive response to 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) opening

When responder has ca. 6+ HCP, they should make a positive response of 1![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png).

Opener rebids as follows:

- With both minor suits (at least 5-4) and minimum strength, they rebid 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png).
    - Responder can then relay with 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) to ask opener to rebid their longer (or stronger if equal length) minor at the 2-level - or, if short in both minors, improvise some other bid.
- With a balanced (4333, 4432, and 5332) hand and 18-19 HCP, they rebid 1![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png).
    - Responder's rebids are analogous to the [responses to a 1NT opening bid](#Responses_to_1NT_opening) (albeit taking into account that opener's point range is 18-19 HCP, not g12-14 HCP).
- With 6+ clubs and mininum strength, they rebid 2![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png).
- With 6+ diamonds and mininum strength, they rebid 2![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png).
- With both minor suits (at least 5-4) and a strong hand, they rebid 2![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png).
    - Responder can then relay with 2![NT](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/NT.png) to ask opener to rebid their longer (or stronger if equal length) minor at the 3-level - or, if short in both minors, improvise some other bid.
- With 6+ clubs and a strong hand, they rebid 3![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png).
- With 6+ diamonds and a strong hand, they rebid 3![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png).

#### <a name="Weak_jump_responses_to_1C_opening"> Weak "jump" responses to 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) opening

When responder has a very weak hand with a long suit (ideally 7+ cards) - such that their hand is essentially worthless unless their suit is the trump suit - they can make a weak "jump" response of 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png), 2![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png), 2![D](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/D.png) or 2![H](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/H.png). (Note that 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png) and 2![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) are not technically jumps over 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png).)

Opener should usually pass, though may choose to do otherwise with a strong hand and a good fit for responder's long suit (or if they feel than playing in their long minor will be better).

##### An example

A very weak hand with long spades that should make a weak "jump" response of 1![S](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/S.png):

> ![spade](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/spade.png)QT87542![heart](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/heart.png)32![diamond](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/diamond.png)J3![club](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/club.png)96 -- unbalanced (**7**=_2_=_2_=_2_) | 3 HCP

#### <a name="Coping_with_interference_after_1C_opening"> Coping with interference after 1![C](https://raw.githubusercontent.com/aornota/redneck/main/src/resources/C.png) opening

_Coming soon..._