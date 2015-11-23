# FOMmiR

MicroRNA Prediction Using a Fixed-Order Markov Model
Based on the Secondary Structure Pattern

# Introduction

Predicting miRNAs is an arduous task, due to the diversity of the precursors and complexity of enzyme processes. Although
several prediction approaches have reached impressive performances, few of them could achieve a full-function recognition
of mature miRNA directly from the candidate hairpins across species. Therefore, researchers continue to seek a more
powerful model close to biological recognition to miRNA structure.

In this project, we describe a novel miRNA prediction
algorithm, known as FOMmiR, using a fixed-order Markov model based on the secondary structural pattern. For a training
dataset containing 809 human pre-miRNAs and 6441 human pseudo-miRNA hairpins, the model’s parameters were defined
and evaluated.

The results showed that FOMmiR reached 91% accuracy on the human dataset through 5-fold crossvalidation.
Moreover, for the independent test datasets, the FOMmiR presented an outstanding prediction in human and
other species including vertebrates, Drosophila, worms and viruses, even plants, in contrast to the well-known algorithms
and models. Especially, the FOMmiR was not only able to distinguish the miRNA precursors from the hairpins, but also
locate the position and strand of the mature miRNA.

Therefore, this study provides a new generation of miRNA prediction
algorithm, which successfully realizes a full-function recognition of the mature miRNAs directly from the hairpin sequences.
And it presents a new understanding of the biological recognition based on the strongest signal’s location detected by
FOMmiR, which might be closely associated with the enzyme cleavage mechanism during the miRNA maturation.

# Availability

Online serivce: http://bioinf.shenwei.me/cgi-bin/FOMmiR.cgi

# Citing FOMmiR

- Shen W, Chen M, Wei G, Li Y* (2012) MicroRNA Prediction Using a Fixed-Order Markov Model Based on the Secondary Structure Pattern. PLoS ONE 7(10): e48236. doi:[10.1371/journal.pone.0048236](http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.0048236)
