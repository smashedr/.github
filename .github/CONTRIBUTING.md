# Contributing

- [Workflow](#Workflow)
- [Testing](#Testing)

If you need help with a pull request, please
[contact support](https://github.com/cssnr/.github/blob/master/.github/SUPPORT.md#support).

## Workflow

1. Fork the repository.
2. Create a branch in your fork.
3. Make your changes.
4. Do any applicable [Testing](#Testing).
5. Commit and push your changes.
6. Create a PR to the source repository.
7. Verify the checks pass, otherwise resolve.
8. Complete all applicable tasks.
9. Make sure to keep your branch up-to-date.

## Testing

Many Repositories include a Test workflow that runs on a `pull_request` when possible.  
However, secrets are not available on this trigger; therefore, workflows with secrets only run on the `push` trigger.

You can run a `push` trigger Test in your own repository by enabling workflows on the fork.
If the only secret used is `secrets.GITHUB_TOKEN` that is automatically generated and requires no action.
Other secrets needed to be manually added to the GitHub Secrets in the Repository Settings.

# Support

Please consider making a donation to support the development of this project
and [additional](https://cssnr.com/) open source projects.

[![Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/cssnr)

For a full list of current projects visit: [https://cssnr.github.io/](https://cssnr.github.io/)
