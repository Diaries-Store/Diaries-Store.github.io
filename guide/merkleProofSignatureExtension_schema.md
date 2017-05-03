---
layout: guide
guide_back: true
---
## MerkleProof2017 schema

An extension that allows an issuer to issue an Open Badge on the blockchain and provide proof of inclusion in a blockchain transaction. This uses the Chainpoint v2.0 specification: [https://chainpoint.org/](https://chainpoint.org/)

The schema defines the following properties:

### `type` (JsonLdType, required)

### `merkleRoot` (string, required)

### `targetHash` (string, required)

### `proof` (array, required)

The object is an array with all elements of the type `object`.

The array object has the following properties:

#### `right` (string)

#### `left` (string)

### `anchors` (array, required)

The object is an array with all elements of the type `object`.

The array object has the following properties:

#### `sourceId` (string)

#### `type` (string)

---

# Sub Schemas

The schema defines the following additional types:

## `JsonLdType`

A type or an array of types defined in a JSON-LD context file.

This property must be one of the following types:

* `string`
* `array`