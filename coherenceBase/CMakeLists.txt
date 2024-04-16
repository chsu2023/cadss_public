project(coherenceBase)
add_library(coherenceBase SHARED coherence.c protocol.c stree.c)
target_include_directories(coherenceBase PRIVATE ../common)
