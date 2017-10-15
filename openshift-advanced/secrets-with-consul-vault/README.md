# dpeloying cluster of consul as statefulset
# each pod contains 2 containers (vault, cosnul)
# Cronjob runs every hour to snapshot consul for any sudden crash
# Cronjob mounts a PVC to write the date on

