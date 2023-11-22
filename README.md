# gh action-version

This `gh` extension enables you to fetch the commit SHA of GitHub Actions.
It's particularly useful when you need to pin a specific action revision in your workflows:

```
- uses: actions/checkout@b4ffde65f46336ab88eb53be808477a3936bae11 # v4.1.1
```

## Install
```
gh extension install taiki45/gh-action-version
```

## Usage
To fetch the latest revision of `actions/checkout`, use:

```
gh action-version actions/checkout
```

To fetch a specific version, for instance, `v3`:

```
gh action-version actions/checkout v3
```
