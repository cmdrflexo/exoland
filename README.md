<h1 align="center">Exokit Studio</h1>
<p align="center"><a href="https://exokit.org" target="_blank"><img width="300" height="300" alt="Exokit" src="assets/icon.png"/></a></p>
<p align="center"><b>The ultimate WebXR interface, powered by the <a href="https://github.com/exokitxr/exokit">Exokit Engine</a>.</b></p>

<p align="center">
  <a href="https://github.com/exokitxr/studio/releases"><img src="https://img.shields.io/github/downloads/exokitxr/studio/total.svg"></a>
  <a href="https://www.npmjs.com/package/exokit-studio"><img src="https://img.shields.io/npm/v/exokit-studio.svg"></a>
  <a href="https://github.com/exokitxr/studio/issues"><img src="https://img.shields.io/github/issues/exokitxr/studio.svg"></a>
  <a href="https://github.com/exokitxr/studio"><img src="https://img.shields.io/github/forks/exokitxr/studio.svg"></a>  
  <a href="https://github.com/exokitxr/studio"><img src="https://img.shields.io/github/stars/exokitxr/studio.svg"></a>  
  <a href="https://twitter.com/exokitxr"><img src="https://img.shields.io/twitter/follow/exokitxr.svg?style=social"></a>
</p>

<div align="center">
  <a href="https://exokit.org">Site</a>
  &mdash;
  <a href="https://exokit.org/docs/">Docs</a>
  &mdash;
  <a href="https://discordapp.com/invite/Apk6cZN">Discord</a>
  &mdash;
  <a href="https://twitter.com/exokitxr">Twitter</a>
  &mdash;
  <a href="http://eepurl.com/dFiLMz">Email List</a>
</div>

## Examples

<a href="https://youtu.be/cd_DEwCDF6U"><img alt="Hands Reality Tab" target="_blank" src="https://user-images.githubusercontent.com/29695350/55507781-0e463300-561e-11e9-9b1a-f43b8259d041.gif" height="190" width="32%"></a>
<a href="https://youtu.be/b-UKSg0QCRE"><img alt="Live Reload Magic Leap" target="_blank" src="https://user-images.githubusercontent.com/29695350/55507118-a216ff80-561c-11e9-829e-74d8244571c3.gif" height="190" width="32%"></a>
<a href="https://youtu.be/O1xA1r5SZUM"><img alt="Tutorial Reality Tab" target="_blank" src="https://user-images.githubusercontent.com/29695350/55507125-a3e0c300-561c-11e9-835f-3a26a9e879b5.gif" height="190" width="32%"></a>

<a href="https://www.youtube.com/watch?v=m_QntqZmd_Q"><img alt="Reality Projection with HTC Vive and Magic Leap" target="_blank" src="https://user-images.githubusercontent.com/29695350/55507271-e60a0480-561c-11e9-87ad-7dc736ba0760.gif" height="190" width="32%"></a>
<a href="https://youtu.be/i0MXRCNkdB4"><img alt="Emukit" target="_blank" src="https://user-images.githubusercontent.com/29695350/55507623-a8f24200-561d-11e9-97a3-194b6b4a1d8b.gif" height="190" width="32%"></a>
<a href="https://exokit.org/"><img alt="Various Exokit Apps" target="_blank" src="https://user-images.githubusercontent.com/29695350/55506701-ba3a4f00-561b-11e9-9e19-ba808bed7c5a.gif" height="190" width="32%"></a>

*Find more examples on [YouTube](https://www.youtube.com/channel/UC87Q7_5ooY8FSLwOec52ZPQ).*


## Overview

Exokit Studio **enables developers to build XR experiences with ease** by having a seamless interface to the Exokit Engine. Studio prefers using GUIs instead of command lines with difficult to remember arguments to use the functionality you want.

Studio is uses the [Exokit Engine](https://github.com/exokitxr/exokit), which is written on top of Node and emulates a web browser, providing native hooks for WebGL, WebGL2, WebVR, WebXR, WebAudio, and other APIs used in immersive experiences.

:eyeglasses: **Exokit Engine currently targets the following platforms**:
* OpenVR Desktop VR (Steam compatible)
* Oculus Desktop (Oculus Rift, Oculus Rift S)
* Oculus Mobile (Oculus Quest, Oculus Go, GearVR)
* Magic Leap
* iOS ARKit *
* Android ARCore *
* Google VR (Daydream / Cardboard / Mirage Solo) *
* any XR device, start a [pull request](https://github.com/exokitxr/exokit/compare) to the Exokit Engine with a native binding if it isn't listed here! *

\* not supported yet

:electric_plug: **Exokit Engine powers experiences built with**:
* Three.js
* Unity
* Pixi.js
* Babylon.js
* A-Frame
* Custom WebGL frameworks
* WebAssembly, TypeScript, and any language that transpiles to JavaScript
* Unity WebVR export *
* SteamVR *
* any 3d web framework, start a [pull request](https://github.com/exokitxr/exokit/compare) to the Exokit Engine if a 3d web framework isn't currently supported! *

\* not supported yet

## Quickstart

### Desktop
<h4><a href="https://get.exokit.org">Download and install Studio for current OS</a></h4>

### Local Development

```sh
git clone https://github.com/exokitxr/studio.git
cd studio
npm install
npm build
```

## Stay in Touch

- [Join our Discord](https://discord.gg/Apk6cZN) for discussions.
- [Follow @exokitxr on Twitter](https://twitter.com/exokitxr) for updates.
