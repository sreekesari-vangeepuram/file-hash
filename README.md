# File Hash

A simple CLI tool in Golang to get the hash of a given file.  
Various hash functions are implemented to fetch the checksum.

# Algorithms

| Name 				| Length 			| Type 															|
| ----------------- | ----------------- | ------------------------------------------------------------- |
| BLAKE-256 		| 256 bits 			| HAIFA structure 												|
| BLAKE-512 		| 512 bits 			| HAIFA structure 												|
| BLAKE2s 			| up to 256 bits 	| HAIFA structure 												|
| BLAKE2b 			| up to 512 bits 	| HAIFA structure 												|
| BLAKE2X 			| arbitrary 		| HAIFA structure, extensible-output functions (XOFs) design 	|
| BLAKE3 			| arbitrary 		| Merkle tree 													|
| ECOH 				| 224 to 512 bits 	| hash 															|
| FSB 				| 160 to 512 bits 	| hash 															|
| GOST 				| 256 bits 			| hash 															|
| Grøstl 			| up to 512 bits 	| hash 															|
| HAS-160 			| 160 bits 			| hash 															|
| HAVAL 			| 128 to 256 bits 	| hash 															|
| JH 				| 224 to 512 bits 	| hash 															|
| LSH 				| 256 to 512 bits 	| wide-pipe Merkle–Damgård construction 						|
| MD2 				| 128 bits 			| hash 															|
| MD4 				| 128 bits 			| hash 															|
| MD5 				| 128 bits 			| Merkle–Damgård construction 									|
| MD6 				| up to 512 bits 	| Merkle tree NLFSR (it is also a keyed hash function) 			|
| RadioGatún 		| arbitrary 		| ideal mangling function 										|
| RIPEMD 			| 128 bits 			| hash 															|
| RIPEMD-128 		| 128 bits 			| hash 															|
| RIPEMD-160 		| 160 bits 			| hash 															|
| RIPEMD-320 		| 320 bits 			| hash 															|
| SHA-1 			| 160 bits 			| Merkle–Damgård construction 									|
| SHA-224 			| 224 bits 			| Merkle–Damgård construction 									|
| SHA-256 			| 256 bits 			| Merkle–Damgård construction 									|
| SHA-384 			| 384 bits 			| Merkle–Damgård construction 									|
| SHA-512 			| 512 bits 			| Merkle–Damgård construction 									|
| SHA-3				| arbitrary			| sponge function 												|
| Skein 			| arbitrary 		| Unique Block Iteration 										|
| Snefru 			| 128 or 256 bits 	| hash 															|
| Spectral Hash 	| 512 bits 			| wide-pipe Merkle–Damgård construction 						|
| Streebog 			| 256 or 512 bits 	| Merkle–Damgård construction 									|
| SWIFFT 			| 512 bits 			| hash 															|
| Tiger 			| 192 bits 			| Merkle–Damgård construction 									|
| Whirlpool 		| 512 bits 			| hash 															|

# References
- Unkeyed cryptographic hash functions: [Wikipedia](https://en.wikipedia.org/wiki/List_of_hash_functions#Unkeyed_cryptographic_hash_functions)
