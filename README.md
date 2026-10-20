# scoop-bucket

[Scoop](https://scoop.sh) bucket for apps by [Dandy Garda](https://dandygarda.com).

## Usage

```powershell
scoop bucket add dandygardad https://github.com/dandygardad/scoop-bucket
scoop install lazytfs
```

## Apps

| App | Description |
|---|---|
| [lazytfs](https://github.com/dandygardad/lazytfs) | Terminal UI for Team Foundation Server (TFS) version control, inspired by lazygit |

## Updating a manifest

After publishing a new GitHub release, update the version, URL and hash with Scoop's checkver script:

```powershell
& "$(scoop prefix scoop)\bin\checkver.ps1" -App lazytfs -Dir .\bucket -Update
```
