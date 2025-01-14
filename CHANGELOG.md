# Changelog for Vouch Proxy

## Unreleased

Coming soon! Please document any work in progress here as part of your PR. It will be moved to the next tag when released.

## v0.32.0

- [slack oidc example](https://github.com/vouch/vouch-proxy/blob/master/config/config.yml_example_slack) and [slack app manifest](https://github.com/vouch/vouch-proxy/blob/master/examples/slack/vouch-slack-oidc-app-manifest.yml)
- [CHANGELOG.md](https://github.com/vouch/vouch-proxy/blob/master/CHANGELOG.md)

## v0.31.0

- [use quay.io](https://quay.io/repository/vouch/vouch-proxy?tab=tags) instead of Docker Hub for docker image hosting
- use [httprouter's](https://github.com/julienschmidt/httprouter) more performant mux

## v0.29.0

- embed static assets as templates using [go:embed](https://golang.org/pkg/embed/)

## v0.28.0

- add support for a custom 'relying party identifier' for ADFS

_the rest is history_ and can be teased out with `git log`
