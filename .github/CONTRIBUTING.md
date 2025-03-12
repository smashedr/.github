# Contributing

> [!WARNING]  
> This guide is a work in progress and may not be complete.

# Workflow

1. Fork the repository.
2. Create a branch in your fork.
3. Make your changes.
4. Do any applicable [Testing](#Testing).
5. Commit and push your changes.
6. Create a PR to this repository.
7. Verify the checks pass, otherwise resolve.
8. Make sure to keep your branch up-to-date.

## Testing

Many Repositories include a Test workflow that runs on a `pull_request` when possible.  
However, secrets are not available on this trigger; therefore, workflows with secrets only run on the `push` trigger.

You can run a `push` trigger Test in your own repository by enabling workflows on the fork.
If the only secret used is `secrets.GITHUB_TOKEN` that is automatically generated and requires no action.
Other secrets needed to be manually added to the GitHub Secrets in the Repository Settings.

# Support

For support, view the [SUPPORT.md](https://github.com/smashedr/.github/blob/master/.github/SUPPORT.md).

---

[README](https://github.com/smashedr/.github?tab=readme-ov-file#readme) |
[SUPPORT](https://github.com/smashedr/.github/blob/master/.github/SUPPORT.md#support) |
[CONTRIBUTING](https://github.com/smashedr/.github/blob/master/.github/CONTRIBUTING.md#contributing) |
[SECURITY](https://github.com/smashedr/.github/blob/master/.github/SECURITY.md#security)

[Website](https://cssnr.github.io/) |
[GitHub Organization](https://github.com/cssnr) |
[GitHub Profile](https://github.com/smashedr)
