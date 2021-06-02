# denizenapp/prettier-config

Shared Prettier config for Denizenapp projects.

## Usage

Usage is based on [Sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations) from the Prettier docs.

1. Remove existing `.prettierrc` file, if present.
1. Install the config directly from Github (for now).

    ```
    npm install -D denizenapp/prettier-config#main
    ```

1. Add the following to `package.json`:

    ```
    "prettier": "prettier-config"
    ```
