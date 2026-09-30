# mtg-multi for MikroTik ARMv7

Builds a RouterOS-importable Docker image tar for **MHSanaei/mtg-multi v1.15.0** on `linux/arm/v7`.

The workflow downloads the upstream ARMv7 release archive, verifies its published SHA-256, builds a minimal image, and exports it with `docker save`.

No MTProxy secrets are stored in this repository.
