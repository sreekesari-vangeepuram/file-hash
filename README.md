# File Hash

A simple CLI tool in Golang to get the hash of a given file.  
Various hash functions are implemented to fetch the checksum.

# Algorithms

| Name 				| Length 			| Type 															| Implemented |
| ----------------- | ----------------- | ------------------------------------------------------------- | ----------- |
| BLAKE-256 		| 256 bits 			| HAIFA structure 												| :x:         |
| BLAKE-512 		| 512 bits 			| HAIFA structure 												| :x:         |
| BLAKE2s 			| up to 256 bits 	| HAIFA structure 												| :x:         |
| BLAKE2b 			| up to 512 bits 	| HAIFA structure 												| :x:         |
| BLAKE2X 			| arbitrary 		| HAIFA structure, extensible-output functions (XOFs) design 	| :x:         |
| BLAKE3 			| arbitrary 		| Merkle tree 													| :x:         |
| ECOH 				| 224 to 512 bits 	| hash 															| :x:         |
| FSB 				| 160 to 512 bits 	| hash 															| :x:         |
| GOST 				| 256 bits 			| hash 															| :x:         |
| Grøstl 			| up to 512 bits 	| hash 															| :x:         |
| HAS-160 			| 160 bits 			| hash 															| :x:         |
| HAVAL 			| 128 to 256 bits 	| hash 															| :x:         |
| JH 				| 224 to 512 bits 	| hash 															| :x:         |
| LSH 				| 256 to 512 bits 	| wide-pipe Merkle–Damgård construction 						| :x:         |
| MD2 				| 128 bits 			| hash 															| :x:         |
| MD4 				| 128 bits 			| hash 															| :x:         |
| MD5 				| 128 bits 			| Merkle–Damgård construction 									| :x:         |
| MD6 				| up to 512 bits 	| Merkle tree NLFSR (it is also a keyed hash function) 			| :x:         |
| RadioGatún 		| arbitrary 		| ideal mangling function 										| :x:         |
| RIPEMD 			| 128 bits 			| hash 															| :x:         |
| RIPEMD-128 		| 128 bits 			| hash 															| :x:         |
| RIPEMD-160 		| 160 bits 			| hash 															| :x:         |
| RIPEMD-320 		| 320 bits 			| hash 															| :x:         |
| SHA-1 			| 160 bits 			| Merkle–Damgård construction 									| :x:         |
| SHA-224 			| 224 bits 			| Merkle–Damgård construction 									| :x:         |
| SHA-256 			| 256 bits 			| Merkle–Damgård construction 									| :x:         |
| SHA-384 			| 384 bits 			| Merkle–Damgård construction 									| :x:         |
| SHA-512 			| 512 bits 			| Merkle–Damgård construction 									| :x:         |
| SHA-3				| arbitrary			| sponge function 												| :x:         |
| Skein 			| arbitrary 		| Unique Block Iteration 										| :x:         |
| Snefru 			| 128 or 256 bits 	| hash 															| :x:         |
| Spectral Hash 	| 512 bits 			| wide-pipe Merkle–Damgård construction 						| :x:         |
| Streebog 			| 256 or 512 bits 	| Merkle–Damgård construction 									| :x:         |
| SWIFFT 			| 512 bits 			| hash 															| :x:         |
| Tiger 			| 192 bits 			| Merkle–Damgård construction 									| :x:         |
| Whirlpool 		| 512 bits 			| hash 															| :x:         |

# References
- Unkeyed cryptographic hash functions: [Wikipedia](https://en.wikipedia.org/wiki/List_of_hash_functions#Unkeyed_cryptographic_hash_functions)
