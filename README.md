# Tob Home Row Mods

This repo contains information about setting up home row mods for your system.

It is meant as a guide to help go along with the video by [Dreams of Code](https://youtube.com/@dreamsofcode)

This repo is organized by the different approaches you can take to setting up home row mods.

## General information

Whilst Home Row Mods are a simple concept, there's a lot of variables and configuration that you can
apply to them.

For an in depth guide on home row mods, I recommend reading the following resource. 

[https://precondition.github.io/home-row-mods](https://precondition.github.io/home-row-mods)

In my case, I only have a simple configuration, which works well for my purposes, but might not for you.

## QMK

For an example on how to set up Home Row Mods with QMK, I recommend checking out the [QMK](./qmk) directory

For a real world example, you can check out my [Adm42 config]()

## ZMK

For an example on how to set up Home Row Mods with ZMK, I recommend checking out the [ZMK](./qmk) directory

For a real world example, you can check out my [Glove80 config](https://github.com/elliottminns/glove80-zmk-config).

## Oryx

If you have a keyboard from ZSA, then you can either use QMK, or their own proprietary configurator, Oyrx (as well as Keymapp)

In my case, I have a configuration for both the ZSA Moonlander and the ZSA Voyager, which you can find below

### Moonlander

You can find my Moonlander configuration [here](https://configure.zsa.io/moonlander/layouts/DwbO7/latest/0)

## Kanata

For my laptops, I make use of Kanata, which is a software keyboard remapper. This works well for keyboards where the firmware
can't be customized.

### Linux (systemd)

You can find an example kanata configuration for linux to use with systemd in the [linux directory](./kanata/linux)
