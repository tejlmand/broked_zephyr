To use:

mkdir testing; cd testing;
git clone this repo
west init -l application
west update
cd application

west build -t menuconfig -b nrf52840dk_nrf52840

This was tested with Zephyr SDK v 0.11.4 with Zephyr commit 970a9a02ad8a340817a4bc707b841f5e697dbd15
