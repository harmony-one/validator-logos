# validator-logos
Repository to store validator logos
* The validators logos will be used by several clients such as Harmony staking explorer when displaying the list of validators.


## Steps to add your logo
* Fork this repository
* Add your logo by creating the logo image name using your Harmony one-address and placing it inside `validators/`, e.g. `validators/one1pdv9lrdwl0rg5vglh4xtyrv3wjk3wsqket7zxy.jpg`
* Append your validator basic information to the bottom of the list.json,

For example, append yours to the last lines of list.json

```
...
{
    "id": "one1pdv9lrdwl0rg5vglh4xtyrv3wjk3wsqket7zxy",
    "name": "Harmony",
    "description": "Harmony Staking",
    "website": "https://harmony.one"
},
```

* Create a PR
* Once the Harmony team approves your logo, it will be consumed by clients like Harmony staking explorer




## Image Requirements
- file extension: `png`. Uppercase `PNG` is considered as invalid
- name：file name requirements for: `logo.png` name, but [folder naming](#repository-structure) where they placed is most important part of contribution
- dimension: `256px by 256px` or `512px by 512px`
- size: up to `100 KB`. TIP: use free drag and drop online service [tinypng](https://tinypng.com/) to optimize image size
- background: preferably transparent
