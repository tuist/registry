# Tuist Registry

This repository is bound to a registry where the on-premise images of the Tuist server are published

| Resource | Description |
| ---- | --- |
| [Releases](https://github.com/tuist/cloud-on-premise/releases) | A list of releases along with their release notes. |
| [tuist](https://github.com/orgs/tuist/packages/container/package/tuist) | The Docker image containing Tuist's service to deploy to Linux environments. |
| [tuist-macos](https://github.com/orgs/tuist/packages/container/package/tuist-macos) | The Docker image containing Tuist's service to run it in macOS environments. |

> [!IMPORTANT]
> If you are trying to run Tuist in an Apple Silicon environment, you have to use the [`tuist-macos`](https://github.com/orgs/tuist/packages/container/package/tuist-macos) image. Attempting to run the Linux image will cause the service to blow up at boot time.
