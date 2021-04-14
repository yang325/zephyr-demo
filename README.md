# Zephyr Introduction

The Zephyr OS is based on a small-footprint kernel designed for use on resource-constrained and embedded systems: from simple embedded environmental sensors and LED wearables to sophisticated embedded controllers, smart watches, and IoT wireless applications.

# West

The Zephyr project includes a swiss-army knife command line tool named west. West’s built-in commands provide a multiple repository management system with features inspired by Google’s Repo tool and Git submodules.

## Installing west

```bash
pip3 install --user -U west
```

## Get the demo

```bash
west init -m https://github.com/yang325/zephyr-demo.git zephyr-demo
cd zephyr-demo
west update
```