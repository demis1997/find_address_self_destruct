# find address self destruct

Educational Solidity recovery/selfdestruct exercise for a deployed child contract.

## Source and reproduction

Inspected Solidity: `recovery.sol`. Contracts include `Recovery`, `SimpleToken`. Source compiler pragmas: `^0.6.0`.

No complete pinned compiler/dependency build harness was found in the inspected files. Import resolution and automated execution are unverified; an isolated local test harness is required before running the example.

This is a prototype/security-study example. Do not interpret the source as audited production code or execute it against third-party deployments. No on-chain transaction was performed.

No repository-wide license file was found; no license has been assigned by this maintenance change.

## Existing notes and attribution

# find_address_self_destruct
 
When you interact with the contract, the address will show on etherscan and since self destruct was open to the public then we used that to force send ourselves the eth and destroy the contract. 
We simply re-created the self destruct function and entered our own address while running it from within the original contract

<img width="1536" alt="recovery" src="https://user-images.githubusercontent.com/63403890/186525957-8eecc2c4-3254-4a9f-981d-604d31c562ae.png">
