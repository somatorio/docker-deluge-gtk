# deluge-gtk

## How to use
```
docker run -d \
        --name deluge \
        -e DISPLAY \
        -v /tmp/.X11-unix/:/tmp/.X11-unix/ \
        -v $HOME/.config/deluge:/root/.config/deluge \
        -v $HOME/Torrents/:/root/Torrents \
        somatorio/deluge-gtk
```
