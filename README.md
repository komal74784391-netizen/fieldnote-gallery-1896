# fieldnote-gallery-1896

Registry for research-profile sites built with the Fieldnote static theme.

Each published site ships a `manifest.json` at the root of its site repository.
The crawler validates the manifest against the gallery format every time it
indexes the registry; entries that do not match exactly are rejected and the
site is not listed.

Accepted entries live under `manifests/`. When registering a new site, conform
to the entries already accepted there; they are the format of record.
