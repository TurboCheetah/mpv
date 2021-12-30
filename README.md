My configuration for mpv. Please keep in mind this is a shitty amalgamation of [Absynth](https://github.com/0xAB51NTH/mpv) and [LightArrowEXE](https://github.com/LightArrowsEXE/dotfiles/tree/master/mpv/.config/mpv)'s configs. Feel free to modify this to your liking, including uncommenting or changing settings however you please.

## How to install the base setup

**Windows:**<br>

1) Create a new folder in `%appdata%` and call it mpv. <br>
2) Dump the contents of this directory in there. <br>
3) Change the paths as necessary in `mpv.conf`.<br>

**Linux:**<br>
TBA


## How to install VapourSynth and the filtering dependencies

1) Install the [latest version of VapourSynth](https://github.com/vapoursynth/vapoursynth/releases).<br>
1.5. Install the latest required version of [Python](https://www.python.org/downloads/), and make sure it's added to PATH.<br>
2) Locate the following directories:<br>
 \* C:\Users\[your username]\AppData\Roaming\VapourSynth\plugins64<br>
 \* C:\Users\[your username]\AppData\Local\Programs\Python\Python39\Lib\site-packages<br>
3) Check the .vpy scripts in the repo (in the `vpy` directory) and follow the links to the listed dependencies.
4) Download and move the required files to the relevant directories (Python modules go to the `site-packages` directory, everything else goes in the `plugins64` directory).
5) Verify that the scripts are running as intended by cycling through the profiles and pressing the `~` key during playback. It should tell you if it failed, and if it did what the missing dependencies are.

### *Optional VapourSynth scripts*

* [VapourSynth](https://github.com/vapoursynth/vapoursynth/releases)
* [havsfunc](https://github.com/HomeOfVapourSynthEvolution/havsfunc/releases)
* [lvsfunc](https://pypi.org/project/lvsfunc/)
* [NNEDI3CL](https://github.com/HomeOfVapourSynthEvolution/VapourSynth-NNEDI3CL/releases)
* [vs-placebo](https://github.com/Lypheo/vs-placebo/releases)
* [vsutil](https://pypi.org/project/vsutil/)

### *For additional shaders and scripts, check out the following sources*

* [mpv shaders](https://github.com/mpv-player/mpv/wiki/User-Scripts#user-shaders)
* [mpv scripts](https://github.com/mpv-player/mpv/wiki/User-Scripts#lua-scripts)
* [VapourSynth scripts](https://github.com/LightArrowsEXE/Encoding-Projects/)

Credits to Absynth and LightArrowEXE