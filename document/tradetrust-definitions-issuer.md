# Untitled object in Open Attestation Schema v3 Schema

```txt
open-attestation/3.0#/properties/issuer
```




| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                       |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [tradetrust.schema.json\*](../out/tradetrust.schema.json "open original schema") |

## issuer Type

`object` ([Details](tradetrust-definitions-issuer.md))

# undefined Properties

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                  |
| :------------------------------ | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                       | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-definitions-issuer-properties-id.md "open-attestation/3.0#/definitions/issuer/properties/id")                       |
| [name](#name)                   | `string` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-definitions-issuer-properties-name.md "open-attestation/3.0#/definitions/issuer/properties/name")                   |
| [identityProof](#identityProof) | `object` | Required | cannot be null | [Open Attestation Schema v3](tradetrust-definitions-issuer-properties-identityproof.md "open-attestation/3.0#/definitions/issuer/properties/identityProof") |

## id

URI when dereferenced, results in a document containing machine-readable information about the issuer that can be used to verify the information expressed in the credential. More information in <https://www.w3.org/TR/vc-data-model/#issuer>


`id`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-definitions-issuer-properties-id.md "open-attestation/3.0#/definitions/issuer/properties/id")

### id Type

`string`

### id Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc4291 "check the specification")

## name

Issuer's name


`name`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-definitions-issuer-properties-name.md "open-attestation/3.0#/definitions/issuer/properties/name")

### name Type

`string`

## identityProof




`identityProof`

-   is required
-   Type: `object` ([Details](tradetrust-definitions-issuer-properties-identityproof.md))
-   cannot be null
-   defined in: [Open Attestation Schema v3](tradetrust-definitions-issuer-properties-identityproof.md "open-attestation/3.0#/definitions/issuer/properties/identityProof")

### identityProof Type

`object` ([Details](tradetrust-definitions-issuer-properties-identityproof.md))
