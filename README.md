# OrcaSlicer User Presets

## Where to put these files

Copy all files and folders from this package into:

```
C:\Users\<YOUR_WINDOWS_USERNAME>\AppData\Roaming\OrcaSlicer\user\default\
```

- Replace `<YOUR_WINDOWS_USERNAME>` with your actual Windows username.
- Overwrite existing files if prompted.
- Subfolders like `process` and `machine` should be placed inside the `default` folder as shown above.

This will make the custom print and machine profiles available in OrcaSlicer.

---

## About the Included Profiles

The provided profiles are organized for Sovol SV06 Plus ACE and similar printers. They are located in the `process` and `machine` subfolders.

### Profile Naming Convention

Profiles use the following naming structure:

```
[layer height] [speed] [support] [printer]
```

- **Layer height**: e.g. `0.10mm`, `0.20mm`
- **Speed**: `VERY SLOW`, `SLOW`, `STANDART`, `FAST`, `VERY FAST`, `INDUSTRIAL`
- **Support**: `NS` = No Support, otherwise support is enabled
- **Printer**: e.g. `SV06 Plus ACE`

**Examples:**
- `0.20mm VERY FAST SV06 Plus ACE` – 0.20mm layer, very fast, with support
- `0.10mm SLOW NS SV06 Plus ACE` – 0.10mm layer, slow, no support

### Experimental Profiles

Some profiles may be marked as `E` (experimental) or have custom settings for testing.

---

## Legend

- `NS` = No Support
- `E` = Experimental
- `STANDART` = Standard
- `INDUSTRIAL` = Standard, but stronger (more walls/infill)
- `edit` = Custom user-edited profile

For a quick reference, see `legenda.txt` in this folder.

