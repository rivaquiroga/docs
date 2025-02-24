---
layout: postag
title: 'VERB'
shortdef: 'verb'
udver: '2'
---

### Definition

A verb is a member of the syntactic class of words that typically
signal events and actions, can constitute a minimal predicate in a
clause, and govern the number and types of other constituents which
may occur in the clause.

Note that the `VERB` tag covers main verbs _(content verbs)_
and _modal verbs_
but it does not cover _auxiliary verbs_ and _copulas,_ for which there is
the [AUX]() tag. (Czech modal verbs are not considered auxiliary.)
See the description of `AUX` for more information on the borderline
between `VERB` and `AUX`.

Czech verbs can take the following morphological forms:

- Infinitive (this is the citation form)
- Finite verb (indicative and imperative forms; conditional is constructed periphrastically)
- Active past participle (used to construct past and conditional)
- Converb (also called transgressive, adverbial participle or gerund)

There are participial forms that are tagged as adjectives ([ADJ]()) rather than verbs.
See below for examples.

A verbal noun can be derived productively from almost every verb
(e.g. _dělat_ &nbsp;“to do” → _dělání_ &nbsp;“doing”).
While in other languages a corresponding form may be called gerund and tagged `VERB`,
in Czech it is tagged [NOUN](). It has always the neuter [cs-feat/Gender]()
and it inflects for [cs-feat/Number]() and [cs-feat/Case]().

### Examples

- _nést_ &nbsp;“to carry”
- _nesu, neseš, nese, neseme, nesete, nesou_ &nbsp;“I carry, you carry, he/she/it carries, we carry, you carry, they carry”
- _nes, nesme, neste_ &nbsp;“carry” (imperative in different persons and numbers)
- _nesl, nesla, neslo, nesli, nesly_ &nbsp;“carried” (past participle in different genders and numbers)
- _nesa, nesouc, nesouce_ &nbsp;“carrying” (present converb in different genders and numbers)

### Border cases

Passive participles lie on the border between verbs and adjectives.
Since release 2.0, both short and long forms are tagged `ADJ`, although
they may have verbal features in addition to the adjectival ones.
For example:

- Short: _nesen, nesena, neseno, neseni, neseny_ &nbsp;“carried”
- Long: _nesený, nesená, nesené, nesení, nesené_ &nbsp;“carried”

Their meaning is almost identical but the usage slightly varies.
Both groups can be used in nominal predication with [copula](cs-dep/cop).
Only the short forms can be used to form the passive voice
(but it may be sometimes difficult to distinguish from copula constructions, see [AUX]()).
On the other hand, the long forms inflect for case and thus
can modify nouns. (Occasionally even the short form may inflect for case
but it is extremely rare in the modern language. Example:
_nesenu_ is the short form of feminine singular accusative.
The corresponding long form is _nesenou_.)

There is an analogy with some adjectives that preserved so called nominal (short) forms.
And these adjectives are not derived from verbs. Example:

- Short (nominal) forms: _stár, stára, stáro_ &nbsp;“old”
- Default long (pronominal) forms: _starý, stará, staré_ &nbsp;“old”

The nominal forms are used in predication,
the standard forms both in predication and to modify nouns.

### References

- [Loos, Eugene E., et al. 2003. Glossary of linguistic terms: What is a verb?](http://www-01.sil.org/linguistics/GlossaryOfLinguisticTerms/WhatIsAVerbLinguistics.htm)
- [Wikipedia](http://en.wikipedia.org/wiki/Verb)
<!-- Interlanguage links updated So kvě 14 19:01:58 CEST 2022 -->
