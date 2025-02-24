---
layout: postag
title: 'NOUN'
shortdef: 'noun'
---


## NOUN : noun 

###  Definition

Nouns typically denote entities such as persons, places, things, animals or ideas.

The tag <code>NOUN</code>  is intended for common nouns only. See <code>PROPN</code> for proper nouns and <code>PRON</code> for pronouns.

Certain adjectives are considered nouns. As such they disallow the formation of comparatives (but not all adjectives allow for comparatives anyway).


Modern Greek expresses degree modification of nouns with a variety of morphological (and syntactic) means:

*	Diminutives (*υποκοριστικά* / *ipokoristika*) productively formed with suffixes such as  *–άκι* / *-aki*, *–ιτσα* / *-itsa*, *–ούλης* / *-oulis*, *-άκης* / *-akis*, *-άκιας* / *-akias* like *χταποδάκι* / *chtapodaki* "little octopus", *παιδάκι* / *pedaki* "little child", *μικρούλα* / *mikroula* "little girl",  *φωνίτσα* / *fonitsa* "little voice": they are assigned the lemma of the original noun and the feature <code>el-DegreeMod</code> takes the value <code>Diminutive</code> . 
* Augmentatives  (*μεγεθυντικά* / *megethintika*)  productively formed with suffixes such as *-άρας* / *-aras*, *-αράς* / *-aras* like  *τρυπάρα* / *tripara* "large hole", *ψευταράς* / *pseftaras* "great lier": they are assigned the lemma of the original noun and the feature <code>el-DegreeMod</code>  takes the value <code>Magnifier</code>.
*	Lexicalised diminutives and augmentatives such as  *λακκάκι* ‘dimple’, *σουβλάκι* / *souvlaki* "roasted pieces of meat on a little spit", *παιχταράς* / *pechtaras* "excellent (football) player": they are not defined for the feature <code>el-DegreeMod</code>. 

Greek nouns inflect for [el-feat/Gender](), [el-feat/Number]() and [el-feat/Case](). Certain nouns do not inflect, but they can be assigned full morphological characterisation, e.g., *δοξαπατρί* / *doksapatri*  "right between the eyes", *τουμπεκί* / *toubeki* "tombako used in a hookah". Such words often occur as cranberry words in multiword expressions.  

###  Examples


*   *γυναίκα* / *gineka* "woman", *σκύλος* / *skilos* "dog", *τραπέζι* / *trapezi* "table", *επανάσταση* / *epanastasi* "revolution", *ελευθερία* / *freedom* "liberty"
* Professions such as *αστυνομικός* / *astinomikos* "policeman", *στρατιωτικός* / *stratiotikos* "military officer". When the same words cooccur with another noun, such as *αστυνομικός σκύλος* / *astinomikos skilos* "police dog", they are assigned the tag <code>ADJ</code>.
* *ακουστικό* / *akoustiko* "head phone/hearing aid", *(καρτο-)κινητό* / *(karto-)kinito* "mobile phone (with a card)", *ενδότερα* / *endotera* "inner parts", *πρωϊνό* / *proino* "breakfast", *μεσημεριανό* / *mesimeriano* "lunch", *βραδινό* / *vradino* "dinner", *λαδερά* / *ladera* "vegetable dishes cooked in olive oil", *λαϊκή* "open market", *περιπολικό* / *peripoliko* "patrol car", etc.
  
### References 

Karra, Athanasia.  2006. *Problems of inflection and of diminutives formatino in Modern Greek and the other European systems.* PhD Thesis (in Greek). University of Patras.   https://nemertes.library.upatras.gr/jspui/bitstream/10889/911/1/Nimertis_Karra.pdf 

<!-- Interlanguage links updated So kvě 14 19:01:49 CEST 2022 -->
