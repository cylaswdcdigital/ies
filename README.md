# IES

## Programmers
Select Tools -> UsbAsp


## How to install
#### Boards Manager Installation
This installation method requires Arduino IDE version 1.8.0 or greater.
* Download Zadig.exe
* Plug in UsbAsp Programmer (MUST BE DONE BEFORE RUNNING ZADIG)
* Click Options > List All Devices (Make sure its selected)
* Select USBasp
* Click Replace Driver (May not be needed if required driver is already installed. Zadig will let you know)
* Open the Arduino IDE.
* Open the **File > Preferences** menu item.
* Enter the following URL in **Additional Boards Manager URLs**:

    ```
    https://cylaswdcdigital.github.io/ies/package_cylaswdcdigital_ies_index.json
    ```

* Open the **Tools > Board > Boards Manager...** menu item.
* Wait for the platform indexes to finish downloading.
* Scroll down until you see the **IES AVR Boards** entry and click on it.
* Click **Install**.
* After installation is complete close the **Boards Manager** window.

