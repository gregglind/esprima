Mozilla Specific Code Parsing
==================================

This branch

* allows starless generators by default. (https://github.com/gregglind/esprima/tree/harmony-starless-yield)
  (see:  https://github.com/ariya/esprima/pull/110 for discussion)

* we don't allow 'each', and throw instead.  (each is from E4X and might fade without warning)
  (see:  https://github.com/ariya/esprima/pull/109)

To build this branch:

1. follow the 'ariya/harmony' branch, including force updating as necessary
2. merge in https://github.com/gregglind/esprima/tree/moz-diff commit.
3. updated moz, moz-diff


