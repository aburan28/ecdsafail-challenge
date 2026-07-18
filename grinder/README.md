# Candidate225 search helper

This branch contains a frozen parent operation stream and the detached nonce
prefilter used to search the six proof-backed CCZ removal circuit. It is search
infrastructure only; none of these files are part of an ecdsa.fail submission.

The workflow partitions one requested interval into 20 disjoint shards and
uploads the prefilter logs for exact local replay.
