# Setup

- Install QMK Firmware: https://docs.qmk.fm/#/newbs_getting_started

- Install QMK Toolbox: https://github.com/qmk/qmk_toolbox

- Clone repo: `git clone https://github.com/pedrus16/qmk_firmware --recurse-submodules`

- Run `qmk config user.keyboard=keebio/bfo9000`

- Run `qmk config user.keymap=pedrus16`

- From repo root run `qmk compile`

- In QMK Toolbox, select the `qmk_firmware/keebio_bfo9000_pedrus16.hex` file

- Plug your Elite-C

- Press the reset button if the peripheral is not recognized by QMK Toolbox

- Click *Flash*