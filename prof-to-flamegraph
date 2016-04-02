#!/bin/bash

# We use d2u to convert Windows line endings to Unix for flamegraph.pl
# (ghc-prof-flamegraph inadvertently produces Windows line endings - should fix this.)

cat $1.prof | ghc-prof-flamegraph | d2u | flamegraph.pl > $1.svg