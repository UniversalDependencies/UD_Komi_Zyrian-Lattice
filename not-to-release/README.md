Processing pipeline will be described here. The scripts used will be updated and maintained, and currently these are the versions used in creating 2.2. and developing upcoming 2.3. release. The history is somewhat messy due to different parts of the treebanks being done while coming up with different practices. 

The backbone of the tools used is [Giellatekno](http://giellatekno.uit.no/) infrastructure for Komi-Zyrian. In order to test the workflows used here, installing the Giellatekno tools is necessary. Setting up the system is described [here](http://giellatekno.uit.no/doc/infra/GettingStarted.html) and [here](http://giellatekno.uit.no/doc/infra/infraremake/GettingStartedWithTheNewInfra.html). One of the other tools tested within the pipeline, but not yet integrated, is KyungTae Lim's [Multilingual BIST Parser](https://github.com/jujbob/multilingual-bist-parser), and we are actively looking for solutions that would use a wider stack of modern NLP methods.

## Example

Here will be a concrete example of how to get from plain text to an annotated sentence in the treebank.

## Unfinished tasks

- Some tags are currently missing, current situation has to be checked
- Some extra validation is needed for correcting manual errors, i.e. "check that all nouns have case tag"
- Language tags have to be double-checked in IKDP
- Russian items currently missing animacy and gender categories
- Some Russian features such as Case=Loc not in feature file yet
- English translations would be nice

## Question

- POS tag of ниӧти?
- POS tag and analysis of кодь?
- на as an adverb or particle?
- идралӧм, босьтӧм as VERB
- Abbreviations, what to do with с.в. etc.
- Some compounds should be broken apart, i.e. партийно-комсомольскӧй
- Consistency of сэтшӧм and татшӧм