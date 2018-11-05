# auth0-scripts
Custom rules and login pages to use with Resound.  The custom rule is necessary if you want to set Resound up in multi-tenancy mode.

There are two ways to use this repo:

1. contact the maintainer and give them your auth0 webhook info. (easiest)
1. fork this and set up a webhook in that fork to your own Auth0 account (see installation below)

## prerequisites
1. an Auth0 account and tenant
1. [Auth0 webhook values](https://auth0.com/docs/extensions/github-deploy#configure-the-extension)

## installation
1. configure the extension as stated in [Auth0's documentation here](https://auth0.com/docs/extensions/github-deploy#configure-the-extension)
1. deploy any changes from the repo that is hooked up to the webhook in the above step
