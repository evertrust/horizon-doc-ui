# horizon-doc-ui

This is the default UI for Horizon, forked from [the Antora default UI](https://gitlab.com/antora/antora-ui-default).

## Developing locally

To bundle the UI locally, install required packages with npm:
```shell
npm i
```

Then bundle the UI with gulp:
```shell
npx gulp bundle
```
## CI Workflow

The token provided as a secret for the webhook.yml workflow requires write right on **Contents** on the [doc.evertrust.fr](https://github.com/evertrust/docs.evertrust.fr) repository. Via a webhook, it triggers the build and deployment of the documentation.
