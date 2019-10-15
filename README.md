#### Make Bootable USB


```sh
sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/"target_USB" --applicationpath /Applications/Install\ macOS\ High\ Sierra.app --nointeraction
```

#### Clover EFI Bootloader Configuration
![alt text](https://raw.githubusercontent.com/normansyarif/EFI-Dell-E6420/master/Utils/Clover%20config.png)

#### Install High Sierra on HFS+ instead of APFS
```sh
/Volumes/"Image Volume"/"install macOS High Sierra.app"/Contents/Resources/startosinstall --volume /Volumes/"HighSierra" --agreetolicense --converttoapfs NO
```