# vpxtool-fe
SDL3 based GUI frontend for vpxtool

## Running

For now you need to run this using the rust toolchain.

```shell
cargo run --release
```

When running under Wayland (Linux), you need to force the use of XWayland to be able to position windows.

```shell
SDL_VIDEODRIVER=x11 cargo run --release
```

## Acknowledgements

Inspire by on https://github.com/surtarso/ASAPCabinetFE
