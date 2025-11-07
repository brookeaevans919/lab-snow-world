# lab-snow-world
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Unreal Snow World</title>
    <script src="https://aframe.io/releases/1.5.0/aframe.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/aframe-environment-component@1.3.1/dist/aframe-environment-component.min.js"></script>
  </head>
  <body>
    <a-scene>
      <!-- Environment preset -->
      <a-entity environment="preset: yavapai; groundColor: #ffffff; skyColor: #b3e5fc;"></a-entity>

      <!-- Snowman -->
      <a-entity position="0 0 -5">
        <a-sphere position="0 1 0" radius="1" color="#fff"></a-sphere>
        <a-sphere position="0 2 0" radius="0.7" color="#fff"></a-sphere>
        <a-sphere position="0 2.8 0" radius="0.5" color="#fff"></a-sphere>
        <a-sphere position="-0.15 2.9 0.45" radius="0.05" color="#000"></a-sphere>
        <a-sphere position="0.15 2.9 0.45" radius="0.05" color="#000"></a-sphere>
        <a-cone position="0 2.8 0.55" radius-bottom="0.05" height="0.2" color="orange" rotation="90 0 0"></a-cone>
        <a-cylinder position="0 3.1 0" radius="0.3" height="0.2" color="#000"></a-cylinder>
        <a-cylinder position="0 3.3 0" radius="0.15" height="0.4" color="#000"></a-cylinder>
      </a-entity>

      <!-- Camera -->
      <a-entity camera position="0 1.6 0"></a-entity>
    </a-scene>
  </body>
</html>
