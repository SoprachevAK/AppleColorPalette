## Quick Package Install

#### Using UnityPackageManager (for Unity 2019.3 or later)
Open the package manager window (menu: Window > Package Manager)<br/>
Select "Add package from git URL...", fill in the pop-up with the following link:<br/>
https://github.com/SoprachevAK/AppleColorPalette.git<br/>

#### Using UnityPackageManager (for Unity 2019.1 or later)

Find the manifest.json file in the Packages folder of your project and edit it to look like this:
```js
{
  "dependencies": {
    "com.soprachevak.apple-color-palette": "https://github.com/SoprachevAK/AppleColorPalette.git",
    ...
  },
}
```

<!-- DOC-START -->
<!-- 
Changes between 'DOC START' and 'DOC END' will not be lost on package update 
-->

## Description
Add colors (scripts, material, presets) from apple guidelines

| Name          |     HEX       | Color         |
| ------------- |:-------------:|:-------------:|
| White         |   #FFFFFF     | ![](https://placehold.it/15/FFFFFF/000000?text=+)      |
| Black         |   #000000     | ![](https://placehold.it/15/000000/000000?text=+)      |
| Blue          |   #007AFF     | ![](https://placehold.it/15/007AFF/000000?text=+)      |
| Green         |   #4CD964     | ![](https://placehold.it/15/4CD964/000000?text=+)      |
| Orange        |   #FF9500     | ![](https://placehold.it/15/FF9500/000000?text=+)      |
| Pink          |   #FF2D55     | ![](https://placehold.it/15/FF2D55/000000?text=+)      |
| Purple        |   #5856D6     | ![](https://placehold.it/15/5856D6/000000?text=+)      |
| Red           |   #FF3B30     | ![](https://placehold.it/15/FF3B30/000000?text=+)      |
| Teal Blue     |   #5AC8FA     | ![](https://placehold.it/15/5AC8FA/000000?text=+)      |
| Yellow        |   #FFCC00     | ![](https://placehold.it/15/FFCC00/000000?text=+)      |

## Usage
* From script: 
  ```csharp 
  Color color = AppleColorPalette.AColor.<<color>>;
  ```
* From material: Contains Opaque and Transparent material with Standard shader and enabled GPU Instancing   
* From preset: Choose Apple Color Pallet in any unity's color picker 

<!-- DOC-END -->

## Author

**Soprachev Andrei**


## Show your support

Give a ⭐️ if this project helped you!