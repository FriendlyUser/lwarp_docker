# lwarp-docker
lwarp docker image for personal use. This docker image is meant for personal use for my notes.


## Procedure to Transfer images

If using github codespaces use 

```
cat ./TOKEN.txt | docker login https://docker.pkg.github.com -u FriendlyUser --password-stdin
```
where TOKEN.txt has a PAT with write access