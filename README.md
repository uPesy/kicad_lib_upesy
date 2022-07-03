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
  <img src="https://github.com/uPesy/kicad_lib_upesy/raw/master/assets/add_env_path_kicad.PNG" width="500">
</p>

- Go to Preferences > Manage Symbol Libraries, and Add the global library `uPesy Boards` : `${UPESY_BOARDS}/uPesy.kicad_sym`

<p align="center">
  <img src="https://github.com/uPesy/kicad_lib_upesy/raw/master/assets/add_symbol_path.PNG" width="500">
</p>

- Go to Preferences > Manage Footprint Libraries, and Add the global library `uPesy Boards` : `${UPESY_BOARDS}/uPesy.pretty`

<p align="center">
  <img src="https://github.com/uPesy/kicad_lib_upesy/raw/master/assets/add_footprint_path.PNG" width="500">
</p>

> For KiCad v5, use `uPesy.lib` instead of `uPesy.kicad_sym`

## ⚖️ License

The uPesy Kicad libraries are licensed under the [Creative Commons CC-BY-SA 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/legalcode), with the following exception :

*To the extent that the creation of electronic designs that use 'Licensed Material' can be considered to be 'Adapted Material', then the copyright holder waives article 3 of the license with respect to these designs and any generated files which use data provided as part of the 'Licensed Material'.*

**What does this mean?**

uPesy Kicad libraries are licensed in such a way to ensure free use of library data for commercial, closed, and non-commercial projects without restriction. uPesy does not wish to exert any control over designs produced using the library data, or force users to reveal proprietary information contained in their designs. Neither do we wish to force users to attribute the uPesy Kicad libraries within their design.

Use of the library data in a project does not (by itself) require that the design or any files generated from the design are licensed under the CC-BY-SA 4.0 License. You are free to use the library data in your own projects without the obligation to share your project files under this or any other license agreement.

However, if you wish to redistribute the uPesy Kicad libraries, or parts thereof (including in modified form) as a collection then the exception above does not apply. Redistributed library collections must be shared under the same license agreement. Under these circumstances, the libraries must also retain attribution information, including the license documents which are distributed with the library files.

## 🔧 Warranty

The uPesy Kicad libraries are provided in the hope that they will be useful, but are provided without warranty of any kind, express or implied.
If you find an error in the library data, please help the community and contribute a fix !