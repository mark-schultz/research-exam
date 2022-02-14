TOPIC: Coding theory in Lattice Cryptography

Main idea is to survey uses of quantization within lattice-based cryptography.
To keep separate from my work with Daniele, I will focus on quantization-type
techniques within the realm of KEMS, which would require a different framework
than that encryption. The main idea would be to build a good picture of the
NewHope-type line of work of quantized KEMs, and perhaps build a framework with
lower bounds (although there was a separte framework for kems built in 12/20).

The KEMs used in practice are direct sums of quite low dimensional lattices (say
D_4, or even Z), which in my experience with quantized LWE behave rather poorly.
It may be interesting to examine quantizing KEMs with lattices that do not have
a ``low-dimensional direct sum'' structure.
