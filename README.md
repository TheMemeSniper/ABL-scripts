# ABL-scripts
Default scripts repo for ANTIBODYLauncher

# Ribosome script manager documentation

update()
Ribosome fetches `repoindex.py` from a raw `githubusercontent` URL. This can be changed to *any* URL, as long as it's raw text. Once it has this file, it creates a checksum for it and compares it to the current index's checksum for that repo on the machine. If it's different or doesn't exist, then the old repoindex is deleted and replaced with the new repoindex.
