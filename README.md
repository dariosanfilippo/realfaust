# realfaust
This library contains a set of functions representing domain-limited 
versions of all Faust primitives and math functions that can potentially 
generate INF or NaN values. The goal of the library is to be able to 
implement DSP networks that, structurally, are free from INF and NaN 
values. Hence, the resulting programs should be rock-solid during real-time 
performance and virtually immune to crashes regardless of how mercilessly
a network is modulated or how unstable a recursive system is made.
