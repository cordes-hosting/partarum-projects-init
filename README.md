# partarum-projects-init

> Bitte in das Terminal vom Projekt kopieren und ausführen
> 
> Für die letzte Version - sofern ich mit dem Dokumentieren nicht hinterherkomme - vielleicht erstelle ich noch ne Action dafür
>
>```shell
> mkdir tmp; wget $(curl --silent "https://api.github.com/repos/cordes-hosting/partarum-projects-init/releases/latest" | jq -r '.tarball_url') -O - | tar -xz -C tmp/ && rsync -a tmp/$(ls tmp)/ . && rm -r tmp && bash .partarumGhost/bin/initPartarumDev
>```
>