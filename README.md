# Johns OrcaSlicer Presets

Orca slicer profiles for Sovols SV06 plus ACE printer. (as well as a custom printer profile and some bonus filaments)
Made for private use, shared for friends. (aka dont expect much) 
If you have any comments/improvements, dont hesitate to make a comment/issue. I might come around to reading them one day.

## Where to put these files

Copy all files and folders from this package into:

```
C:\Users\<YOUR_WINDOWS_USERNAME>\AppData\Roaming\OrcaSlicer\user\default\
```

- Replace `<YOUR_WINDOWS_USERNAME>` with your actual Windows username.
- Overwrite existing files if prompted.
- Subfolders like `process` and `machine` should be placed inside the `default` folder as shown above.

---

## About the Included Profiles

The provided profiles are organized for Sovol SV06 Plus ACE and similar printers. They are located in the `process` and `machine` subfolders.

### Profile Naming Convention

Profiles use the following naming structure:

```
[layer height] [speed] [support] [printer]
```

- **Layer height**: e.g. `0.10mm`, `0.20mm`
- **Speed/Purpose**: `VERY SLOW`, `SLOW`, `STANDART`, `FAST`, `VERY FAST`/ `INDUSTRIAL`,`TPU` etc.
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
- `INDUSTRIAL` = Standard, but stronger (more walls/infill)
- `edit` = Edited version of a default/premade/stolen profile
