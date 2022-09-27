# Signature Verifications with Solidity 

Offchain signed messages, with on chain verfication using an Ethereum message signing format.

<img width="892" alt="Screen Shot 2022-09-27 at 11 34 32 am" src="https://user-images.githubusercontent.com/7098556/192410825-2fda1715-0cae-4df5-aa0b-8f4c5ca1ef6d.png">

## GET STARTED

This project uses a [task runner called just, for convenience](https://github.com/casey/just)

```
Available recipes:
    default
    install *PACKAGES
    update
    compile
    deploy-localhost
    deploy-testnet
    verify-testnet
    test
    lint
    start
    format
    audit
    print-audit
    print-gas-usage
    print-deployments
    clean
```

### Running tests and audits

- Run the unit tests with `just test`
- Statically analyse code for vulnerabilities with `just audit` 
