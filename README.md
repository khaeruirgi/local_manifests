# Local Manifests #
Just grab the manifest and sync to get device sources

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/khaeruirgi/local_manifests/main/local_manifests.xml --create-dirs

# Sync
repo sync -j$(nproc --all) --force-sync
```
