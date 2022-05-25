# LunCo – vision video
Video that explains what LunCo (Lunar Colony) sim is about

This video is a compulation of opensource projects builds using Godot.

The beauty of opensource is that you do not have to reinvent the wheel.

LunCo will incorporate certain mechanics as well as contribute to development of modules it's build from

## Development process
1. Uses **git lfs** to store binary files e.g. Blender, meshes, etc
2. Blender 3.1.2 video sequencer
3. Godot 3.5-rc2

### How to use **git lfs**
<details>
    <summary>
        How to install git lfs (click to expand)
    </summary>

   1. Install git lfs:

   1.1 MacOS: 

    brew install git-lfs

   1.2 Other OS:

    [git lfs](https://git-lfs.github.com)

   1. Activate **git lfs** (once on computer):

            git lfs install
</details>

<details>
    <summary>
        How to clone and use this repo with git lfs (click to expand)
    </summary>
1. Clone repo:

    git lfs clone git@github.com:LunCoSim/lunco-vision-video.git

2. If repo cloned without lfs:
   a. Goto to directory

        cd lunco-vision-video
   b. type 

        git lfs pull

3. Now all the Blender models will be downloaded to your computer. Start using them!

4. Push & pull binary files as reqular
</details>

<details>
    <summary>
        How to commit binary files (click to expand)
    </summary>

1. Create .gitattributes
2. Add all you'd like to track like in .gitignore

</details>

## References
- [Moonwards](https://www.moonwards.com/) – opensource Lunar City in Godot, lot of assets under MIT
- [iVoyager](https://www.ivoyager.dev) – a development platform for creating games and educational apps in a realistic solar system, Godot, Apache 2.0

## Assets
1. [Starship model](assets/spacex-starship) created by [MartianDays](https://sketchfab.com/3d-models/spacex-starship-a8a0b69f776841a1a465cd9fb3762fd2)
2. [NASA Moon CGI KIL](https://svs.gsfc.nasa.gov/4720)