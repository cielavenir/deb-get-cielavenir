## deb-get-cielavenir

[deb-get](https://github.com/wimpysworld/deb-get) external repo.

Note that you are _highly_ encouraged to setup `DEBGET_TOKEN` when using this.

## usage

```
echo https://raw.githubusercontent.com/cielavenir/deb-get-cielavenir/master/01-cielavenir | sudo tee /etc/deb-get/01-cielavenir.repo
```

Then you can `deb-get update` as always.
