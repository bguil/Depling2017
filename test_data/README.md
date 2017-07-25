# Test data

This folder contains the data used in the evaluation part of the Depling 2017 article _Enhanced UD Dependencies with Neutralized Diathesis Alternation_

## Test data from **UD_French-Sequoia**
**SEQ_test** contains 100 sentences from **UD_French-Sequoia**

  * Input data tajen from V2.0 of UD data:
    * `SEQ_test_pa-.conllu` data extracted from the corpus **UD_French-Sequoia**
    * `SEQ_test_pa+.conllu` same data as before with manual annotation of:
      * which _par_-phrases are agents of passives
      * which instances of the reflexive clitic _se_ correspond to an alternation promoting object to subject
      * which complement of a causative complex predicate _faire_+Infinitive correspond to the subject of the infinitive
  * Data with enhanced dependencies and diathesis alternation produced with Graph Rewriting rules (in two settings):
    * `SEQ_test_pa-_ogre.conllu` the data obtained with **Ogre** applied to `SEQ_test_pa-.conllu`
    * `SEQ_test_pa+_ogre.conllu` the data obtained with **Ogre** applied to `SEQ_test_pa+.conllu`
    * `SEQ_test_pa-_grew.conllu` the data obtained with **Grew** applied to `SEQ_test_pa-.conllu`
    * `SEQ_test_pa+_grew.conllu` the data obtained with **Grew** applied to `SEQ_test_pa+.conllu`
  * Data with enhanced dependencies and diathesis alternation manually annotated
    * `SEQ_test_gold.conllu` Gold data

## Test data from **UD_French**
**UD_test** contains 100 sentences taken from **UD_French**

  * Input data tajen from V2.0 of UD data:
    * `UD_test_pa-.conllu` data extracted from the corpus **UD_French-Sequoia**
    * `UD_test_pa+.conllu` same data as before with manual annotation of:
      * which _par_-phrases are agents of passives
      * which instances of the reflexive clitic _se_ correspond to an alternation promoting object to subject
      * which complement of a causative complex predicate _faire_+Infinitive correspond to the subject of the infinitive
  * Data with enhanced dependencies and diathesis alternation produced with Graph Rewriting rules (in two settings):
    * `UD_test_pa-_ogre.conllu` the data obtained with **Ogre** applied to `UD_test_pa-.conllu`
    * `UD_test_pa+_ogre.conllu` the data obtained with **Ogre** applied to `UD_test_pa+.conllu`
    * `UD_test_pa-_grew.conllu` the data obtained with **Grew** applied to `UD_test_pa-.conllu`
    * `UD_test_pa+_grew.conllu` the data obtained with **Grew** applied to `UD_test_pa+.conllu`
  * Data with enhanced dependencies and diathesis alternation manually annotated
    * `UD_test_gold.conllu` Gold data

