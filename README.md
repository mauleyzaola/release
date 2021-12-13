# release

## Deployment

To spin a new release, run this command

```bash
export GITHUB_TOKEN="YOUR_GH_TOKEN"
git tag -a v0.1.0 -m "First release"
git push origin v0.1.0
goreleaser release --rm-dist
```