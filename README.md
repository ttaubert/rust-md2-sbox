# md2-sbox

A Rust library to compute MD2's S-box.

The S-box for MD2 is given in [RFC 1319](http://tools.ietf.org/html/rfc1319)
without explaining how exactly it was derived from the digits of PI. This
library computes the S-box as
[described by Ron Rivest](http://crypto.stackexchange.com/a/18444/12164).

# License

MPL 2.0
