# Remote Install - Harmony Checkpoint

Remotely install Harmony Check Point Anti Virus on an endpoint.

  This was made for the unattended installation of Harmony Check Point AntiVirus package for Windows machines.  Per Harmony's documentation, this is using PSTools - PsExec.exe for the silent installation.

  This tool will download the PsExec.exe from Microsoft but you will need to supply the EndpointSetup.exe generated from Harmony Check Point Infinity Portal.  You can supply this to the users machine via an RMM or host your own file repository and direct PowerShell to your repository.

Unfortunately, since each Harmony package generated is specific to the client, this will not be 100% unattended, but it's close and saves us a decent amount of time.

![harmonypwsh1](https://user-images.githubusercontent.com/110135593/230750481-376dd30e-461a-4f1b-80f7-fc277bb553a2.jpg)
