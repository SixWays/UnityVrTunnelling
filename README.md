# UnityVrTunnelling
Simple Unity implementation of *Tunnelling* for VR - dynamic reduction of FOV to combat sim-sickness

*Tunnelling*, as seen in Ubisoft's Eagle Flight, is dynamic vignetting to reduce FOV in VR while rotating. This reduces perceived motion for players and can be highly effective in reducing sim-sickness. This Unity image effect implementation is designed to be simple and easily extended.

## Use
Just attach to a camera and link the Ref Transform field to the player's vehicle or body (i.e. something which determines their gross rotation in the world - NOT the HMD). The default settings should work ok for most situations.

Note that Tunnelling.shader must be in the Resources folder, or the shader will work in editor but not in builds.

## Example
![Tunnelling in Sublevel Zero](blob:https%3A//drive.google.com/d0dcd038-dde6-4d64-9eee-d1f132760f8b)