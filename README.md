My research rxam for my Masters at UCSD (our analogue of qualifying exams, see [this](https://cse.ucsd.edu/graduate/exams/phd-research-examination-overview)).

The initial goal of it was to survey lattice-based KEM design, for which there
are broadly two distinct approaches

* "Reconciliation-based KEMs", which build IND-CPA-based KEMs directly (perhaps
  the best-known example of this is the inital submission to CCS of the
  ``[NewHope](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/alkim)'' scheme), and
* "Encryption-based KEMs", which the initial LPR-type scheme is used, before
  building a KEM with the FO-transform. Every LWE-based NIST finalist is of this
  form, meaning FrodoKEM, Saber, Kyber.

Note for the NewHope scheme one has to be a little careful in the particular
version you look at --- they later switched over to be an encryption-based KEM
for their NIST submission, so in particular the round 2 NIST candidate NewHope is encryption-based, while the CCS paper linked above is reconcilliation-based

I tried to write everything in terms of the [*Framework for Cryptographic
Problems from Linear Algebra*](https://eprint.iacr.org/2019/282.pdf), while also
discussing how one can highlight how KEM design is guided by the choice of a few
(implicit) coding-theoretic choices.

While I would change many things about the exam+talk, I am leaving all documents (roughly) in the same form that I submitted them, up to the comments that my committee asked me to incorporate.
