# README

## *plenat_erf presents*

# **sUiT**

## *(**SIgnal UTility         wifi mapping, on-device**)*

A basic and janky household wifi signal mapping utility for windows. This was written just to learn a few things, but works good enough to publish.

---

## Manual Installation

Check for python install:

```sh
python -V
```

If no python install is found, follow the download and install instructions on the [Python website](https://www.python.org/downloads), or with CMD using the below commands:

```sh
winget source reset
winget install --id Python.Python.3 --source winget
```

Download and extract sUiT.zip, then navigate to the wifi_map folder and open a CMD terminal from this location. 

Install dependencies

```sh
pip install -r pipreqs.txt
```

or alternatively:

```sh
pip install matplotlib
pip install numpy
pip install scipy
```

This is all the setup you need in the terminal, though you **_MUST ENSURE THERE IS AN IMAGE FILE OF THE FLOORPLAN IN THIS CURRENT FOLDER (wifi_map)_**. This can be named anything, but must be the only image file in the folder.

Once the floorplan image is in place, start the mapping tool with

```sh
python wifi_map.py
```

---

## Contributing

Contributions are always welcome!

Please email the [maintainer](mailto:joshuasturre1@gmail.com) to get involved!

---

## Acknowledgements

- Shout out to StackOverflow and Reddit, always got the answers.

---

## Contact OWNER AUTHOR AND MAINTAINER

- Joshua Sturre -- [joshuasturre1@gmail.com](mailto:joshuasturre1@gmail.com)
