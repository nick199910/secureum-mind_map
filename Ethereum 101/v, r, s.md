# 40 - v, r, s

**_r_ and _s_** are the two parts of the ECDSA signature produced by the transaction originator using the private key. 

**_v_** is the recovery identifier which is calculated as either one of 27 or 28, or as the chain ID (Ethereum mainnet chainID is 1) doubled plus 35 or 36. (See [here](https://github.com/ethereumbook/ethereumbook/blob/develop/06transactions.asciidoc#digital-signatures))

---
## Slide Text
- ECDSA Signature -> 65 Bytes
- r, s -> signature
- 32 bytes each
- v -> recovery identifier 1 byte
- v -> 27 or 28 or
- chainID*2 + 35 or 36

---
## Code Examples
```
# seth chain
ethlive

# seth chain-id
1
```