# UnityVrTunnelling
Simple Unity implementation of *Tunnelling* for VR - dynamic reduction of FOV to combat sim-sickness

## DEPRECATED
This package is now deprecated - our advanced plugin [VR Tunnelling Pro is now open source](https://github.com/sigtrapgames/VrTunnellingPro-Unity) and is strongly recommended over this repo.

## Tunnelling

*Tunnelling*, as seen in Ubisoft's Eagle Flight, is dynamic vignetting to reduce FOV in VR while rotating. This reduces perceived motion for players and can be highly effective in reducing sim-sickness.

## Use
Just attach to a camera and link the Ref Transform field to the player's vehicle or body (i.e. something which determines their gross rotation in the world - NOT the HMD). The default settings should work ok for most situations.

Note that Tunnelling.shader must be in the Resources folder, or the shader will work in editor but not in builds.

## Cubemaps
Supports drawing a cubemap in the vignette for a "cage" effect.

## VR Tunnelling Pro
For many more features, including masking, 3D cage, full cross-platform support, presets and a mobile-friendly version, see our upcoming Unity Asset Store plugin VR Tunnelling Pro: [www.sigtrapgames.com/vrtp](http://www.sigtrapgames.com/vrtp)

## Example
![Tunnelling in Sublevel Zero](https://gifyu.com/images/tunnelling.gif)
