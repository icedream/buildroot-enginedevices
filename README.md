# Buildroot customizations for engine OS devices

This repository contains configuration, patches and package files for Buildroot
to target devices that normally run Denon's engine OS.

## References

### Device info

- MPC Live Internals: https://niklasnisbeth.gitlab.io/mpc-internals/
- Adapting MPC-LiveXplore to Denon Prime 4: https://github.com/TheKikGen/MPC-LiveXplore/issues/37
- Unbricking inMusic Products: https://github.com/RedHate/Unbricking-inMusic-Products

### Firmware info

Not yet supported stuff:

- A look at Denon's modern signed images (says SC Live but contains info for PRIME 4 Plus): https://github.com/TheKikGen/MPC-LiveXplore/issues/51

### Buildroot

- Keeping customizations outside of Buildroot: https://buildroot.org/downloads/manual/customize-outside-br.txt
- On patches: https://buildroot.org/downloads/manual/customize-patches.txt
