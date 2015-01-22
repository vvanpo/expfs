
expfs
-----
Expandable filesystem

- A file-based filesystem, meaning it is not fixed within a partition or other block-device but is instead variably-sized (i.e. a regular file)
- Transparent encryption (optional)
- Transparent compression (optional)
- FUSE-based
- To be used as a simple way of implementing encryption for services like Dropbox, Google Drive, S3, etc.
