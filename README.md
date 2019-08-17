# gh-actions-beta-notes

My notes and links created during the github actions beta

## Develop and run them locally

Run them locally - https://github.com/nektos/act

## Secrets

Don't use them in the beta if you care about them being "secret"
See https://developer.github.com/actions/managing-workflows/storing-secrets/

> "Warning: _**Do not store production secrets**_ in the API during the limited public beta period. Production workflows should not be used during the limited public beta."

- Think about the permissions you are giving your integrations. Use least privilege. 
- Setting up permisisons isolated service accounts is one way to help with that.

## Action Links and Examples
- [Awesome Actions](https://github.com/sdras/awesome-actions)  <-- great collection

## Take-Aways
- GitHub actions could potentially replace most, if not all of my current github app use cases. I wonder what this means for the future of github apps?
  - [Trigger a custom webhook](https://developer.github.com/actions/managing-workflows/triggering-a-repositorydispatch-webhook/)
  
