3gpp-amrwb
==========

amrnb codec from 3gpp offical websit http://www.3gpp.org/DynaReport/26204.htm

These word comes from official document:

The present document contains an electronic copy of the ANSI-C code for the
Floating-point Adaptive Multi-Rate Wideband codec. This floating-point codec
specification is mainly targeted to be used in multimedia applications or in
packet-based applications. The bit-exact fixed-point ANSI-C code in 3GPP TS
26.173 remains the preferred implementation for all applications, but the
floating-point codec may be used instead of the fixed-point codec when the
implementation platform is better suited for a floating-point implementation.
It has been verified that the fixed-point and floating-point codecs
interoperate with each other without any artifacts.

The floating-point ANSI-C code in the present document is the only standard
conforming non-bit-exact implementation of the Adaptive Multi-Rate Wideband
speech transcoder (3GPP TS 26.190 [2]), Voice Activity Detection (3GPP TS
26.194 [6]), comfort noise generation (3GPP TS 26.192 [4]), and source
controlled rate operation (3GPP TS 26.193 [5]). The floating-point code also
contains example solutions for substituting and muting of lost frames (3GPP TS
26.191 [3]).

The fixed-point specification in 26.173 shall remain the only allowed
implementation for the 3G AMR-WB speech service and the use of the
floating-point codec is strictly limited to other services.

The floating-point encoder in the present document is a non-bit-exact
implementation of the fixed-point encoder producing quality indistinguishable
from that of the fixed-point encoder. The decoder in the present document is
functionally a bit-exact implementation of the fixed-point decoder, but the
code has been optimized for speed and the standard fixed-point libraries are
not used as such.

license
=======

I don't know what license it is using, all these code can get from official 
freely.
