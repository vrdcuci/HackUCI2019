# HackUCI2019
Created by VR@UCI


VR@UCI's Facebook Page: https://www.facebook.com/VRatUCI/
VR@UCI's Discord: https://discord.gg/dRKF2Pz


This project contains:
-SteamVR Plugin for Unity version 1.2.3

-Oculus Integration for Unity version 1.31

-VRTK sourced from GitHub

-A Sample scene containing everything you need to start hacking in VR


VRTK GitHub: https://github.com/thestonefox/VRTK
VRTK Documentation: https://vrtoolkit.readme.io/docs


The provided sample scene contains:
-A plane

-A Directional Light

-SDK Manager: This contains all the camera rigs for the VR platforms you are supporting.
	The SteamVR SDK gameobject contains the play area for the SteamVR Platform, both the Oculus Rift and HTC Vive will run on SteamVR.
	You can create a Oculus SDK gameobject if you would like your project to be able to run through the Oculus VR program, but this will only support the Oculus Rift.
	The VR Simulator gameobject contains something that allows you to test your project without a VR headset. It allows you to simulate a headset and two controllers using a keyboard and mouse.

-VRTK Scripts: This contains all the gameobjects that represent your hands, and player.
	Any scripts that are designed to be housed on the hands should be placed on the hand gameobjects within this VRTK Scripts.
	Any scripts for locomotion, body presence, or the play area should be placed on the Player gameobject within VRTK Scripts.
