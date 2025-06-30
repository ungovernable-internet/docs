# API Reference

This section will document the public APIs, endpoints, and smart contract interfaces for UIP.

## Node API
- `GET /status` - Returns node status and health
- `POST /store` - Store content on the network
- `GET /retrieve/:hash` - Retrieve content by hash

## Smart Contract Interfaces
- `registerDomain(name, contentHash)`
- `updateDomain(name, newContentHash)`
- `resolveDomain(name)`
- `transferDomain(name, newOwner)`
- `getOwner(name)`

More details and examples will be added as the implementation progresses.
