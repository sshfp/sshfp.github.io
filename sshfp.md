# SSHFP Well-Known Resource Identifier

This document defines the use of the "/.well-known/sshfp" identifier.

The data MUST only be considered accurate if the request was done via HTTPS.

For the current version, the data is served with the "application/json" MIME type. This may change in future versions of the standard.

# Purpose

The SSHFP Well-Known Resource Identifier is used for verifying the SSH host fingerprint of hosts under a specific domain.

# Example

See [https://cynthia.re/.well-known/sshfp](https://cynthia.re/.well-known/sshfp) for an example.

# Registration Info

URI suffix: "sshfp"

Change controller: Cynthia Revström, [https://cynthia.re](https://cynthia.re), [d6035904-6d06-4ef2-861b-81090738b440@email.cynthia.re](mailto:d6035904-6d06-4ef2-861b-81090738b440@email.cynthia.re)

Specification: this document