# Role

A single role, which can get assigned to create a permission.

## Properties

| Name          | Type           | Description                                                           |
| :------------ | :------------- | :-------------------------------------------------------------------- |
| `appAddress`  | `String`       | App address.                                                          |
| `description` | `String`       | Description of the role. E.g. `"Mint tokens"`.                        |
| `grantees`    | `Permission[]` | Permissions assosiated to the role.                                   |
| `hash`        | `String`       | Encoded identifier for the role.                                      |
| `name`        | `String`       | Identifier of the role. E.g. `"MINT_ROLE"`.                           |
| `manager`     | `String`       | Address of the role manager.                                          |
| `params`      | `String[]`     | Params associated to the role. E.g. `[ "Receiver", "Token amount" ]`. |
