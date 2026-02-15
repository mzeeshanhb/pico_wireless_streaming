Project: High‑Speed Wireless Data Streaming with Raspberry Pi Pico 2 W
This project demonstrates a fast binary data‑streaming pipeline between a Raspberry Pi Pico 2 W and a PC over WiFi.
The Pico sends structured binary packets over TCP, and the PC receives them and measures the upload speed.

What’s included:

Pico sender code (Arduino‑style environment)

Python receiver script

Live speed measurement

Binary packet streaming (no CSV formatting)

What’s not included yet:

Real sensor integration

ADC sampling

Data decoding/visualization

CSV conversion

Lab‑specific sensing tasks

The current version streams synthetic data to test throughput.
Next steps will involve connecting real sensors and adapting the system to a lab use case.