# YASB Custom Theme

A rather simple theme for YASB with the idea of keeping it minimalistic while having nice visuals with Acrylic effects.
<br/>
This cannot be hosted on the official YASB themes repo due to its complex CSS structure which I personally want to keep that way to make it easier to extend and modularize.

<p>
    <a href="https://www.buymeacoffee.com/frostybiscuit" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
</p>

## Prerequisites

 - Install YASB from https://github.com/amnweb/yasb
 - Follow the setup instructions and make sure the status bar loads without issues

## How to apply

 - Download this repository as a .zip package [here](https://github.com/frostybiscuit/yasb-config/archive/refs/heads/master.zip)
 - Open the explorer and navigate to **C:/Users/{USERNAME}/.config/yasb**
 - *(Optional)* Backup your current **config.yaml** and **styles.css**
 - Paste the contents of the .zip into your **yasb** folder
 - Rename **config.public.yaml** to **config.yaml**
 - Rename **.env.sample** to **.env**
 - *(Optional)* Open the **.env** file and change the Weather API key and location if you want to use the weather widget

## Configuration

### Widgets
If you want to configure the widgets I would highly suggest to check the documentation on the official [YAML repository](https://github.com/amnweb/yasb/blob/main/docs/Configuration.md).

### Styling
As for the styling, it would also be best to follow the guides and examples from the YAML documentations. But if you only want to adapt some colors, font-sizes and maybe spacings, simply open the **styles.css** from the root folder and adapt the variables to your liking.<br>
The individual widget styles are then located in **/styles/widgets**.

## Known issues

 - Due to the modular CSS structure, changing anything in the imported .css files *(within the styles folder)* will not trigger an immediate reload. To reload the styles you need to change and save the main **styles.css**

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
