# Manyfold

## Install notes
### Model storage
I created a directory on the host called `/srv/manyfold` for model storage. I had to explicity set the owner to `1000` (the same GUID and UID used by my container). `chown 1000:1000 /srv/manyfold` 

## References
- https://manyfold.app/get-started/docker
