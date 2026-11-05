# Nightstack

A single-page web app that shoots a run of short "long exposures" of the night sky with your phone camera,
then overlays them:

- **Clear sky**: aligns the stars (drift and rotation) and averages the frames to cut noise.
- **Star trails**: keeps the brightest pixel from every frame so the stars draw arcs.
- **Comet trails**: star trails that fade toward the start.

You can also stack photos you've already taken, or try it on a simulated sky.

Browsers only open the camera on https or localhost, so host it on GitHub Pages (Settings → Pages → deploy from `main`, root)
or run `python3 -m http.server 8000` and open http://localhost:8000.
