# NFS World Server Mods for Balap Liar-ID

This repo contains assets that our server use.
Please note that these files are licensed under AGPL-3, means that you are obliged to make your version of this repository open-sourced, keep the license, and credit us if you want to use these files.

## Configuring
`buildconfig.json` holds the primary configuration of the mod packager.
```json
{
    "packages": [
        {
            "source_name": "assets",
            "distribution_name": "balapliarid"
        }
    ],
    "generate_index": true
}
```
- `source_name` - the name of your mod pack inside `src/` folder
- `distribution_name` - name of bundled mod pack (output file) in the `output/` folder
- `generate_index` - whether or not to create an `index.json` that contains mod bundles' name and checksum for the game launcher to use

For modpack configuration, see [README.md](src/README.md)

## Building

`git clone` this repository and `cd` into the folder
```
git clone https://github.com/Plyrs1/blid-server-assets
cd blid-server-assets
```

Then download ModPackager (https://github.com/SoapboxRaceWorld/ModPackager/releases/), extract the contents (just the files without folder) to the `modpackager` folder.

Then you can just run `build.bat` or `build.sh` (WIP), depending on your operating system, and then you can find the resulting mod package inside `output` folder.

## Acknowledgement

Here are the lists of our wonderful modders that are contributing to the community

<table width="100%">
    <thead>
        <tr>
            <th style="text-align: center" width="20%">Name</th>
            <th style="text-align: center" width="20%">Contribution</th>
            <th style="text-align: center">Lists</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center"><img src="https://cdn.discordapp.com/avatars/295511574263889921/a_003aeee6ee68800cda235f6e2c8e8e7c.gif" width="50" height="50" /><br /><sub>Miku Racing</sub></td>
            <td align="center">Project Owner</td>
            <td align="center">-</td>
        </tr>
        <tr>
            <td align="center"><img src="https://cdn.discordapp.com/avatars/210098396113928192/a_d6c36cec65df10f2a4d059c42958e966.gif" width="50" height="50" /><br /><sub>Plyrs</sub></td>
            <td align="center">Developer</td>
            <td align="center">Managing infrastructure</td>
        </tr>
        <tr>
            <td align="center"><img src="https://cdn.discordapp.com/avatars/244343879476707329/6af98f88f3d9372417f62c484863c12d.png" width="50" height="50" /><br /><sub>Fadeli Surya</sub></td>
            <td align="center">Game Master</td>
            <td align="center">Editor Content</td>
        </tr>
        <tr>
            <td align="center"><img src="https://cdn.discordapp.com/avatars/494890873738231808/ce51c507157dcd2244947facb8239fec.png" width="50" height="50" /><br /><sub>Vee</sub></td>
            <td align="center">Modder</td>
            <td align="center">3D Model</td>
        </tr>
        <tr>
            <td align="center"><img src="https://cdn.discordapp.com/avatars/761478857186344970/d6fd936eb326e6e480581f871a0997b5.png" width="50" height="50" /><br /><sub>Initial R</sub></td>
            <td align="center">Modder</td>
            <td align="center">Police Vinyl</td>
        </tr>
        <tr>
            <td align="center"><img src="https://cdn.discordapp.com/avatars/311837422109589505/388f5757962eabbc609a46d91a0aafde.png" width="50" height="50" /><br /><sub>Aditblue</sub></td>
            <td align="center">Modder</td>
            <td align="center">Banner Design</td>
        </tr>
        <tr>
            <td align="center"><img src="https://cdn.discordapp.com/avatars/391989140347944960/1b389a734a4d9b770a5712c71c2206dc.png" width="50" height="50" /><br /><sub>AROGAN</sub></td>
            <td align="center">Modder</td>
            <td align="center">Tuner</td>
        </tr>
        <tr>
            <td align="center"><img src="https://cdn.discordapp.com/avatars/694097958034997269/330c765db782a923d83f6b492fcc088f.png" width="50" height="50" /><br /><sub>Kudungga</sub></td>
            <td align="center">Modder</td>
            <td align="center">3D Model & Tuner</td>
        </tr>
    </tbody>
</table>
