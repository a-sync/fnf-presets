⚠️ This idea was abandoned in favor of [arma3pregen](https://github.com/a-sync/arma3pregen).

# [Friday Night Fight](https://www.fridaynightfight.org/) Arma 3 Launcher presets

## Why?
 * changes tracked via VCS
 * based on standard Arma 3 Launcher preset files
 * downloads generated on the fly with selected optional mods

## Sources
The [servers-and-mods](./servers-and-mods) folder is considered the single source of truth.  

The currently used presets are defined in the [presets.json](./servers-and-mods/presets.json) file.  

All preset information (name, included DLCs, required and optional mods) are parsed from the preset files.  

## Runing locally
Fetch API requires the content to be served via http(s).  
Eg.:  
 - nodejs: `npx serve .`  
 - php: `php -S 0.0.0.0:3000`  
 - python: `python -m http.server 3000`  
