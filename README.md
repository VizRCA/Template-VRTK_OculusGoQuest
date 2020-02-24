# Oculus Go VRTK Template Project

VRTK aims to make building spatial computing solutions in the [Unity] software fast and easy for beginners as well as experienced developers. Please see the VRTK demo project readme for more info at [VRTK](https://github.com/ExtendRealityLtd/VRTK).

## VRTK Warning

VRTK v4 has not yet been released fully is still in the beta phase meaning there may still be undiscovered bugs, missing features and a lack of usable documentation.
If you feel you will struggle figuring stuff out for yourself without detailed documentation then it may be better off if you wait until the full release of VRTK v4.


## Getting Started

### Dependencies and version numbers

+ Unity version: >= 2019.3.2f1
  + Requires Android build system, see [this document for install process](https://docs.unity3d.com/Manual/android-sdksetup.html)
+ VRTK v4, see Disclaimer below.
+ Oculus Integration Version: >= 13.0, Released Feb 7, 2020

### Downloading the project

* Download this project repository to your local machine using *one* of the following methods:
  * Git clone the repository with `git clone https://github.com/VizRCA/Template-VRTK_OculusGoQuest.git`
  * Download the zip file using the button above and **extract it**.

### Opening the downloaded project in the Unity software

> *Do not* drag and drop the project download into an existing Unity project. The repository download *is a Unity project* already and you should not nest a Unity project inside another Unity project. Follow the instructions below for opening the VRTK project within the Unity software. If you only wish to use the VRTK.Prefabs within your own Unity project then follow the [VRTK.Prefabs Getting Started] guide.

#### Using the Unity Hub

* Open the [Unity Hub] panel.
* Click the `Add` Button:

![image](https://user-images.githubusercontent.com/1029673/68544837-112cb180-03bf-11ea-8118-acd2640cfe30.png)

* Browse to the local directory where the repository was downloaded to and click `Select Folder`:

![image](https://user-images.githubusercontent.com/1029673/68544843-1a1d8300-03bf-11ea-9b88-60f55eddf617.png)

* The Template project will now show up in the Unity Hub project window, so select it to open the VRTK project in the Unity software:

![image](https://user-images.githubusercontent.com/1029673/68544856-243f8180-03bf-11ea-8890-1be86159e7f6.png)

* The Template project will now open within the Unity software.

#### Opening from within the Unity software

* Select `Main Menu -> File -> Open Project` within the Unity software.
* Browse to the local directory where the repository was downloaded to and click `Select Folder`.
* The Template project will now open within the Unity software.

### Running the example scene

* Open the `Assets/Scenes/Simple VRTK Oculus Go Scene` scene, or the `Assets/Samples/Farm/Scenes/ExampleScene`.
* Enable `Maximize On Play` in the Unity Game view control bar to ensure no performance issues are caused by the Unity Editor overhead.
* Play the scene in the Unity Editor (`CTRL` + `P`).
* The scene should automatically play within any Unity supported XR hardware.
* Explore the scene and enjoy!

### Building the example scene

* Set up your Oculus Go for development, see below.
* Set up a `Builds` directory outside the project `Assets` folder
* Open `File` > `Build Settings`
  * Make sure example scene is added to scenes in build list.
  * Refresh the `Run Device` list, pick your Oculus Go from the list.
* Press `Build and Run`, put build into previously made `Builds` folder.

#### Set up your Android Device (Oculus Go) for builds

+ On the Oculus phone app, make sure the Oculus Go you are using has developer mode enabled
+ Get your Oculus Signature File ID, follow instructions at https://dashboard.oculus.com/tools/osig-generator/, will require having an Oculus Account.
+ Copy the OSIG credentials file into your Unity project to `Assets/Plugins/Android/assets/` (you may have to make these directories yourself).

## License

Code released under the [MIT License][License]. Check other integrations licenses.

## Disclaimer

These materials are not sponsored by or affiliated with Unity Technologies or its affiliates. "Unity" is a trademark or registered trademark of Unity Technologies or its affiliates in the U.S. and elsewhere.

These materials are not sponsored by or affiliated with VRTK or its affiliates.

[VRTK-Image]: https://user-images.githubusercontent.com/1029673/40060519-bb122e8c-584e-11e8-8402-ca168b327671.png
[Unity]: https://unity3d.com/
[License]: LICENSE.md
[VRTK.Prefabs]: https://github.com/ExtendRealityLtd/VRTK.Prefabs
[VRTK.Prefabs Getting Started]: https://github.com/ExtendRealityLtd/VRTK.Prefabs#getting-started
[Unity Hub]: https://docs.unity3d.com/Manual/GettingStartedUnityHub.html
