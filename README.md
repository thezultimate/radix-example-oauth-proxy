# Radix oAuth2 proxy example
(Based on[radix-example-workshop-1](https://github.com/equinor/radix-example-workshop-1))

Purpose - a simple two module app with a oauth2 proxy in front

## Content

- [echo](./echo) contains the echo module
- [www](./www) contains the www front-end
- [oauth-proxy](./oauth-proxy) contains the OAuth proxy

## Deploying to Radix

* Clone or fork this repository to your own
* Follow the guidelines given in [the Radix documentation](http://www.radix.equinor.com) to create a new application.
* Update the radixconfig.yaml to reflect your setup. The value of metadata.name should be changed to contain the name you give your application
* Follow the documentation of the [oauth-proxy](./oauth-proxy) component to configure Azure AD and the specifics for your applicaition.
* Commit, Push, Rock & Roll

## A conceptual overview of the application.

![Conseptual diagram](./docs/smalldiagram.png) 