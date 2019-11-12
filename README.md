# ensembl-genome-browser-assets

Repo for the wasm-based build-products of ensembl-client. Source is in that repo, not here.
If you have a Rust toolchain, you can also build these assets with only the ensembl-client repo checked out.

We need to move the build products here, into their own repo, to allow us to manage the repo size properly. Do not commit assets to this repo manually: use the WASM build script.
