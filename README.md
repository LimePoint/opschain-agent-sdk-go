# OpsChain Agent SDK for Go

The Go library for building agents that run on OpsChain as governed
operators: enrolment with a registration token, a durable identity, the
outbound-only channel, the mandatory surfaces, the request lane for the
platform API and one correlation scope per unit of work.

This repository is generated from the OpsChain product at each release
and tagged with the product's version; it is not edited here. Start an
agent with the `opschain` binary:

```sh
opschain agent init ./my-agent --lang go
cd my-agent && opschain agent dev
```

The module's first tagged version ships with the OpsChain release that
introduces `opschain agent init`.

## Licence

This software is licensed under the LimePoint End User Licence
Agreement. See [LICENCE](LICENCE). Use requires a valid OpsChain licence.
