# Equalizer APO Presets
## Disclaimers
- Audio drivers will likely interfere with this equalizer. I uninstalled my Realtek driver to circumvent these issues.

## How to use
- Copy "config.txt" and "prestos_bass_preset.txt" to your config directory 
  - The default directory is "C:\Program Files\EqualizerAPO\config"
- Make sure you have "Instant Mode" enabled. This is a checkbox at the top of the Configuration Editor window
- You can add more preset configurations
  - Do this by making your own configuration text file and put it in your config directory
  - In your "config.txt" file, add a line to include your config file
  - For example, if you made a config file called "my_config_file.txt", you would add a line to your "config.txt" like this: 
    - *Include: my_config_file.txt*
