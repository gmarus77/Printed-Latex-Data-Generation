# Printed-Latex-Data-Generation

Python and JS tools for creating Printed Latex Dataset via parsing Cornell's [KDDCUP](https://www.cs.cornell.edu/home/kleinber/kddcup2003.pdf)

COMING:
You can download a prebuilt dataset 180k from [here](https://zenodo.org/record/56198#.V2px0jXT6eA).


**Note: This code is very ad-hoc and requires tinkering with the source**

## Contents
- `Printed_Tex.py`
  - Main module 
- `download_data_utils.py`
  - Contains tools for downlaoding tex tars and unpacking and parisng them.
- `configs.py`
  - Contains Paths and command line script commands.
- `third_party/`
  - Contains Katex for parsing LaTex formulas
- `preprocess_formulas.py` and `preprocess_formulas.js`
  - Collection of tools for handling and parsing LaTex formulas
- `svg_to_png.py`
  - Funcitons to convert LaTex formulas to SVG images using MathJax
- `png_to_svg.py`
  - Funcitons to convert SVG images formulas to PNG images using `inkscape` for (Darwin) MacOS and `rsvg-convert` for all other systems. 
- `Data/`
  - Contains `generated_png_images/` folder, `corresponding_png_images.txt`  and `final_png_formulas.txt`. Also temporary folder `temporary_data` (formulas for various stages of processing and generated SVG images) and `raw_data` where raw data is downloaded.
- `Jupyter Notebooks`
  - Contains examples of generating data using Jupyter notebooks
