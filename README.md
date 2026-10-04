<img src="assets/panomeld-logo.png" alt="PanoMeld logo" width="96" height="96">

# PanoMeld camera profiles

[PanoMeld](https://panomeld.control4all.com/) turns original two-lens photos and supported videos into 360° panoramas. It's free and runs in your browser. Your photos and videos stay on your device.

Camera profiles tell PanoMeld how to line up the two lens images. This repository is a place to find profiles and share ones you've tested.

Other cameras with side-by-side fisheye images may work with a suitable profile too.

## Mi Sphere

[Mi Sphere profile](profiles/mi-sphere.sphere-camera.json) — the same profile included in PanoMeld for Xiaomi Mi Sphere 360. You can use that camera straight away; importing this file is optional.

## Use a profile

1. Open the [editor](https://panomeld.control4all.com/editor/).
2. Go to **Presets → Camera profile → Import JSON** and select the downloaded file.
3. Select the profile and open an original camera file.

Imported profiles stay in your browser. Importing the Mi Sphere file creates a local copy without replacing the built-in one.

## Have a profile to share?

If you've created and tested a camera profile in PanoMeld, please share it so other people can use it too.

Export it with **Camera profile → Export JSON**, then open a pull request adding the file to `profiles/`. Include a short note with the camera model and whether you tested photos, videos or both.

Not familiar with pull requests? Open an issue and attach your profile JSON instead. Share the profile only, not private photos, videos or location data.
