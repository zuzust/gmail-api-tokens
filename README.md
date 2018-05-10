# Gmail API Tokens

Command-line script to authorize a client to call the Gmail API.

## Setup

```bash
# 1. Turn on the Gmail API
# 2. Create credentials for your client
# 3. Authorize your client
```

Read the Node.js Quickstart for more information: https://developers.google.com/gmail/api/quickstart/nodejs

## ENV

The following variables are needed to correctly run the script:

```
export SECRETS_DIR=$(pwd)/secrets
export CLIENT_NAME=your-client-name
```

You can provision them using an `.envrc` file and loading then with [direnv](https://direnv.net/).
