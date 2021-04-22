# Apigee OIDC Mock Provider

This repo contains a standalone Open ID Connect Identity Provider, ready to deploy to Apigee using Hosted Targets.

It leverages [oidc-provider](https://github.com/panva/node-oidc-provider)

It has been configured to meet the CDS Security profile, including support of OIDC Hybrid  flow, mandatory claims and scopes, issuing JWT based identity tokens, etc.

**Important:** This is a sample implementation used only to showcase capabilities. Note that tokens are kept in memory and will be lost if the Mock provider is redeployed or not been used in a while. Also, clients are stored in a configuration file. The installation procedure copies the client app key and secret generated by Apigee into this configuration file.
