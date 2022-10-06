# Getting Started with mmWave Studio

1. Set the Sense On Power (SOP) Jumpers on the mmWave radar sensor to flash programming mode (101). 
<!-- ![sop](/figures/sop.jpg){ width=20% } -->
<p align="center">
  <img src="/figures/sop.jpg" width="600">
</p>
Source: https://www.ti.com/lit/ug/spruim4b/spruim4b.pdf?ts=1665064433434&ref_url=https%253A%252F%252Fwww.google.com%252F
<br>
<br>

2. Unplug the coaxial micro ribbon cable. Connect the mmWave radar sensor to the laptop, and power up the radar.
<!-- ![sop](/figures/unplug_figure.jpg){ width=20% } -->
<p align="center">
  <img src="/figures/unplug_figure.jpg" width="300">
</p>

3. Press  **Win+X** and select **Device Manager**.
4. Check the UART port number.
5. Download [Uniflash](https://www.ti.com/tool/UNIFLASH?utm_source=google&utm_medium=cpc&utm_campaign=epd-der-null-58700007779115394_uniflash_rsa-cpc-evm-google-soas&utm_content=uniflash&ds_k=uniflash&gclid=Cj0KCQjw-fmZBhDtARIsAH6H8qgFQk7WENHo6Pud2rLhGnKesoVYp5XP6u-VkByaYqjwQvnOVJ_wJPYaAtwAEALw_wcB&gclsrc=aw.ds#downloads)
6. Erase the radar using Uniflash

7. Disconnect the power of the mmWave radar 
8. Set the SOP Jumpers on the mmWave radar sensor to Dev mode (011).
9. Plug in the coaxial micro ribbon cable, and Power up the radar.
10. Open the mmWave Radar Studio
