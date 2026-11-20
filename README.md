# AppifyHub · Scoop Bucket

[Scoop](https://scoop.sh/) manifests for [AppifyHub](https://www.appifyhub.com/).

## Using the bucket

Install Scoop using its [official instructions](https://github.com/ScoopInstaller/Install), then add this bucket from PowerShell:

```powershell
scoop bucket add appifyhub https://github.com/appifyhub/scoop-bucket
```

For installing, updating and removing packages, follow the [Scoop documentation](https://github.com/ScoopInstaller/Scoop/wiki). Fully qualified package names use `appifyhub/` as their prefix.

## Adding or removing projects

To add a project, submit a pull request with its manifest in `bucket/<project>.json`, following the official [manifest documentation](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests). To remove a project, submit a pull request deleting its manifest.

## License

[MIT](LICENSE).
