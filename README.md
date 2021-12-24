# HODL

## Install

### Mac

```
brew install truffle
```

## Local Development

1. Compile Code

    ```
    truffle compile
    ```

2. Start Truffle

    ```
    truffle develop
    ```

3. Migrate Smart Contract

    ```
    > truffle migrate
    ```

4. Access Instance

    ```
    > let instance = await [NameOfContract].deployed()
    ```

5. Run Instance Methods

    ```
    > instance.[NameOfMethodOnContract]()
    ```

## Change Log

<details>
<summary>0.1.1</summary>

- smart contract is storing a "state" param
- smart contract methods can accept arguments (message)
- smart contract is migrated w/ default argument 
- user can update "state" param on the smart contract (thus changing the returned message)

</details>
<details>
<summary>0.1.0</summary>

- can run truffle framework 
- can migrate a smart contract
- can access and run functions on a smart contract

</details>