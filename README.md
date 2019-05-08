# singularity-docker-alpine-youtube-dl
alpine container to run youtube-dl (https://github.com/ytdl-org/youtube-dl)


Running without installation:
```
singularity run  library://tru/default/alpine-youtube-dl 
```
Building:
```
sudo singularity build singularity-docker-alpine-youtube-dl.sif  Singularity
```
Download and rename:
```
singularity pull --name singularity-docker-alpine-youtube-dl.sif library://tru/default/alpine-youtube-dl
```
Running with a separate $HOME  (here ~/singularity.d/home/singularity-docker-alpine-youtube-dl)
```
mkdir -p  ~/singularity.d/home/singularity-docker-alpine-youtube-dl
singularity run  -H ~/singularity.d/home/singularity-docker-alpine-youtube-dl singularity-docker-alpine-youtube-dl.sif
```
