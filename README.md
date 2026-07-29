# Ministry of Justice Data Platform User Guide

[![Ministry of Justice Repository Compliance Badge](https://github-community.service.justice.gov.uk/repository-standards/api/data-platform-user-guide/badge)](https://github-community.service.justice.gov.uk/repository-standards/data-platform-user-guide)

[![Open in Dev Container](https://raw.githubusercontent.com/ministryofjustice/.devcontainer/refs/heads/main/contrib/badge.svg)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/ministryofjustice/data-platform-user-guide)

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/ministryofjustice/data-platform-user-guide)

This repository holds the [user guidance](https://user-guide.data-platform.service.justice.gov.uk/) for the [Justice Data Platform](https://data-platform.service.justice.gov.uk/).

## Running locally

The `Makefile` provides the following commands. The `package` and `preview` targets use Docker, so you'll need [Docker](https://www.docs.docker.com/get-docker/) installed and running.

| Command           | Description                                                                                                         |
| ----------------- | ------------------------------------------------------------------------------------------------------------------- |
| `make preview`    | Build and serve the documentation locally for preview at [http://localhost:4567](http://localhost:4567).            |
| `make package`    | Build the documentation into a static site ready for publishing.                                                    |
| `make link-check` | Check for broken links across the Markdown, HTML and ERB files using [lychee](https://github.com/lycheeorg/lychee). |
