# DSCI_310_Example6_Docker

```bash
docker run \
--rm \
-it \
-e PASSWORD="password" \
-p 8787:8787 \
-v /$(pwd):/home/rstudio/work \
mycontainer2
# or rocker/rstudio:4.4.2, inigogrch/mycontainer (last line: container name)
# or -e DISABLE_AUTH=true