# Rancher2 CLI Orb

A Rancher2 CLI orb for CircleCI.

Based heavily on the [doctl orb](https://circleci.com/orbs/registry/orb/digitalocean/cli).

Check out all the details on [CircleCI](https://circleci.com/orbs/registry/orb/brandnewbox/rancher2_cli).

# Local CLI Tar

In August 2022, GitHub failed to compile assets for the latest release of the CLI.

This broke a lot of our stuff, and required massive updates.

So we are going to package a copy of the CLI here, just in case. 

As of August 2022, it is using `rancher-darwin-amd64-v2.6.7-rc1.tar.gz`.

If you intend to update the version, please make sure it unzips. Some did not.

# Updating?

Don't forget to bump the version in `.circleci/config.yml` and in the example in `src/orb.yml` everytime!