# Automotive Solution Center for Simulation e.V.

## Credentials and Schemas
A public repository containing examples for (verifiable) credentials and associated json-ld context definitions. The crendetials are used in the [Decentralized Digital Membership Management](https://ascs.digital).
The DID of issuers and subjects and the UUIDs of the credentials have been aligned with the content of the following example [revocation registry](https://better-call.dev/ghostnet/KT1PZFXebyGvRFG8enbuVL9nrvTi4krYqeKt/storage.)

## Examples
There are two types of json-ld examples for the credentials. The member credentials and the user credential. The member credential is used to e.g. register a company with an application like e.g. [Simpulse](https://simpulse.de) for creating the company profile with minimal validated information. The user credential is used in ascs applications to set initial rights and roles.
The examples are once given with an external context definition and also with the attributes defined directly in the credential. This is necessary as third-party libraries like [didkit](https://github.com/spruceid/didkit) does not allow external context loading due to security implications.

## Resources

* [Implementation Guide](https://www.w3.org/TR/vc-imp-guide/#creating-new-credential-types)
* [w3c credentials v1](https://www.w3.org/2018/credentials/v1)
* [w3c vc-json-schema](https://w3c.github.io/vc-json-schema/)
* [json schema specification](https://json-schema.org/specification)
* [public schemas](https://schema.org/)
* [transform tools](https://transform.tools/)
* [json-ld best practices](https://w3c.github.io/json-ld-bp/?specStatus=ED)
* [version 4 uuid](https://www.uuidgenerator.net/version4)
* [module: pkh-tezos](https://did.js.org/docs/api/modules/pkh_tezos/)
* [did-pkh-method-draft](https://github.com/w3c-ccg/did-pkh/blob/main/did-pkh-method-draft.md)
