# Best Practices for Integrating Tellor

The [TellorUser contract](contracts/TellorUser.sol) in this repository is a reference implementation for integrating Tellor price feed data into your protocol. It demonstrates some best practices for using Tellor, including implementing a dispute time buffer and a data staleness check. It also mitigates back-in-time dispute attacks by caching the most recent value and timestamp. For more information on using Tellor, see the [Tellor documentation](https://docs.tellor.io/tellor/getting-data/solidity-integration).

## Maintainers <a name="maintainers"> </a>
This repository is maintained by the [Tellor team](https://github.com/orgs/tellor-io/people)

## How to Contribute<a name="how2contribute"> </a>  
Check out our issues log here on Github or feel free to reach out anytime [info@tellor.io](mailto:info@tellor.io)

## Copyright
Tellor Inc. 2024