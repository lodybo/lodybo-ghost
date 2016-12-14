# Heroku pre-configured Ghost instance

This repo contains a copy of Ghost, configured to run on an Heroku server.
The custom config file is kept in the `configs` folder, apart from Ghost so that we can easily update it and repackage.

This repo is used as a stand-alone, and as base in the development environment of my Ghost theme.

## Upgrading Ghost
To upgrade Ghost to the latest version:
```bash
npm run upgrade-ghost
```
**Important: This will update Ghost to the latest version, regardless of it being a patch, minor or even major version bump!**

_Todo: Add a way to upgrade to specified version_