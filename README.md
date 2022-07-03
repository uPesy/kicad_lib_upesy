# uPesy Boards KiCad Library

This repo contains Kicad (**v5** and **v6**) libraries for [uPesy Boards](https://www.upesy.com/) with symbols, footprints and 3D models.


## 💾 Installation

- Direct download link : https://github.com/uPesy/kicad_lib_upesy/archive/refs/heads/master.zip and unzip.

- Or clone this repo in your local library folder : 
    ```bash
    git clone https://github.com/uPesy/kicad_lib_upesy.git
    ```


## 🔗 Add libraries in Kicad
Follow these instructions to keep the reference between symbols, footprints and 3D models automatically.

- In KiCad, Go to Preferences > Configure Paths, and add the environment variables `UPESY_BOARDS` with the path to the downloaded folder. For example, 

<p align="center">
  <img src="https://github.com/uPesy/kicad_lib_upesy/raw/master/assets/add_env_path_kicad.png" width="500">
</p>

- Go to Preferences > Manage Symbol Libraries, and Add the global library `uPesy Boards` : `${UPESY_BOARDS}/uPesy.kicad_sym`

<p align="center">
  <img src="https://github.com/uPesy/kicad_lib_upesy/raw/master/assets/add_symbol_path.png" width="500">
</p>

- Go to Preferences > Manage Footprint Libraries, and Add the global library `uPesy Boards` : `${UPESY_BOARDS}/uPesy.pretty`

<p align="center">
  <img src="https://github.com/uPesy/kicad_lib_upesy/raw/master/assets/add_footprint_path.png" width="500">
</p>

> For KiCad v5, use `uPesy.lib` instead of `uPesy.kicad_sym`

## ⚖️ License

The uPesy Kicad libraries are licensed under the [Creative Commons CC-BY-SA 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/legalcode).

## 🔧 Warranty

The uPesy Kicad libraries are provided in the hope that they will be useful, but are provided without warranty of any kind, express or implied.
If you find an error in the library data, please help the community and contribute a fix !