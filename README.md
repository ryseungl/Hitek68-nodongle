# zmk-config-hitek68-no-dongle

Hitek68 ZMK split keyboard firmware — **no-dongle variant**.

Same 68-key board as [zmk-config-hitek68](https://github.com/ryseungl/zmk-config-hitek68),
but without the USB dongle: the **left half is the BLE central** — it pairs
directly to the computer over Bluetooth (or USB when plugged in) and talks to
the right half over BLE. ZMK Studio runs on the left half's USB.

Keymap, matrix, and 30-minute idle sleep are identical to the dongle version.
