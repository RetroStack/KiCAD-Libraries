# KiCAD Libraries

This repository contains the RetroStack symbol and footprint libraries for all RetroStack projects and repositories. To use these libraries, you must install them as global libraries for both types. See the instructions below for installation details.

## Installation Instruction

### Download

Clone this repository onto your local system if you have Git set up, or download the repository as a ZIP file. To do this, click the green "Code" drop-down button and select "Download ZIP." After downloading, unpack the file with your preferred unzip utility.

### Add Symbol Library

- Open KiCAD and stay in the main window of your project (do not enter the schematics or PCB editor).
- Select the "Preferences" menu.
- Choose "Manage Symbol Libraries."
- In the new window, ensure you are on the "Global Libraries" tab.
- Click the "Folder" icon located just below the list.
- Select the "kicad_sym" file from this repository.
- This adds the library to the bottom of the global libraries list.
- Click "OK" to complete the installation of the symbol library.

### Add Footprint Library 

- Open KiCAD and remain in the main window of your project (do not enter the schematics or PCB editor).
- Select the "Preferences" menu.
- Choose "Manage Footprint Libraries."
- In the new window, ensure you are on the "Global Libraries" tab.
- Click the "Folder" icon located just below the list.
- Select the ".pretty" folder from this repository (note that this is a folder, not a file).
- This action adds the library to the bottom of the global libraries list.
- Click "OK" to complete the installation of the footprint library.

## Contents

Below a quick run-down of all the contents of the libraries.

### Symbols

- Various optimized TTL chips to simplify working with them
- Dynamic and static RAM ICs
- Various PROM, EPROM, and EEPROMs
- Breadboard "BusBoard" symbols
- Computer specific symbols (e.g. TRS-80 Model I)
- And others...

### Footprints

- Breadboard "BusBoard" symbols
- All TRS-80 Model I footprints for all components
- And others...

## Support this Project

RetroStack is passionate about exploring and preserving the legacy of older computer systems. Our work involves creating detailed documentation and videos to share our knowledge. We're also dedicated to reviving these classic systems by reimplementing them and offering replacement parts at no cost. If you're keen on supporting this unique project, we invite you to visit our [Patreon page](https://www.patreon.com/RetroStack). Your support would be immensely valuable and greatly appreciated!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
