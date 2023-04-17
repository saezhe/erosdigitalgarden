---
{"dg-publish":true,"permalink":"/1-inbox/lack-of-continuity-in-binary-neural-networks/"}
---

up:: 
pred:: 
ts:: 2023.04.17:11.03.20:847
type:: #zettel
status:: #a
tags:: 

____
# [[1 inbox/lack of continuity in binary neural networks\|lack of "continuity" in binary neural networks]]:

this concern is that the reasoning that removing the messages between neurons being real numbers reduces the capability for gradual change in the learning process, and that bit flips in transfer weights are all or nothing and too savage of a shift.

but let me remind you that under the sending of real numbers in weights are only illusions of such, and under the hood it is actually another network of binary computations transmuting binary signals.

the only key feature of the real transfer functions that make it useful is the fact that some bits within it effect what results more extrememly than others, that gradient of others can then be flipped with less and less consequence.

the gradient of consequence and influence over result is the defining advantageous feature, but we do not need to lose this when we remove real transfer functions for raw binary; the task of optimizing the influence of each neuron is delegated to the training of the network itself, instead of it being handled with an arbitrary "under-overhead" of the module continuous transfer function.

____
# references:

____
template:: [[9 extras/9.100 hidden!/hidden! 8 templates/hidden! 8.01 templater/hidden! 8.01.01 zettels/hidden! 8.01.01 zettel\|hidden! 8.01.01 zettel]]
