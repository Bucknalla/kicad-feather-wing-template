# KiCAD 7 Feather Wing Template

This repo is a simple KiCAD template for Adafruit Feather Wings Specification.
Use it to quickly get started with the standard layout for Feather Wings to build your own sensor, driver, peripheral, etc. Wings.

![board](meta/board.png)

This template is designed for use with [KiCAD 7](https://www.kicad.org/).

## How to use this template

Firstly either `git clone` or download the files in this repo.

Next, you will need to either add these files to your `KICAD_USER_TEMPLATE_DIR` path or change the path to point at this repo.

Typically `KICAD_USER_TEMPLATE_DIR` points at `/Users/your_username/Documents/KiCad/7.0/template/` on MacOS.
Once the path is correctly populated, navigate to `File -> New from Template` and choose `User Templates`.

You should now see a `Feather Wing Template`, select this and begin working on your new project.
Saving the project will prompt you to create a new project.

## Notes

This pinout is specific to the [Adafruit Feather Wing Specification](https://learn.adafruit.com/adafruit-feather/feather-specification) and thus may vary depending on the Feather Board you choose to target. For example, while the mechanical fit is correct, the pin names do not align with the [Feather Huzzah ESP8266](https://learn.adafruit.com/adafruit-feather-huzzah-esp8266/pinouts).

## Reference

- [Adafruit Feather Specification](https://learn.adafruit.com/adafruit-feather/feather-specification)
