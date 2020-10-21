Proof of concept for [macroquad](https://github.com/not-fl3/macroquad)

## For the impatient

    $ podman run -it \
                 -v "$(pwd):/root/src" \
                 -v /tmp/.X11-unix/:/tmp/.X11-unix/ -e DISPLAY=:0 \
                 notfl3/cargo-apk:0.43 \
                 cargo-apk run
