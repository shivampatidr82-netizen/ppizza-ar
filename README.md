<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>

<style>
body{
  margin:0;
  background:#000;
}

model-viewer{
  width:100vw;
  height:100vh;
}
</style>
</head>

<body>

<model-viewer
  src="https://modelviewer.dev/shared-assets/models/Astronaut.glb"
  camera-controls
  auto-rotate>
</model-viewer>

</body>
</html>
