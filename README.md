# TeaTime JSON Database

This is an example [TeaTime](https://github.com/bjesus/teatime/) database that is automatically generated from a JSON files. It uses GitHub Actions to create an SQLite file and then publishes it to GitHub Pages.

## Usage

1. Fork this repository
2. Add your books to [data.json](data.json)
3. Configure your paths at [config.json](config.json)

Make sure to enable Pages in the repository Settings ("Deploy from a branch", "gh-pages"), and to enable "Read and write permissions" under "Actions", "Workflow permissions".

## Serving files

You can make your files available in IPFS using services like [Pinata](https://pinata.cloud) or by running an IPFS node locally.
