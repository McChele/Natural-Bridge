# Natural-Bridge
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Display a map</title>
    <meta
      name="viewport"
      content="initial-scale=1,maximum-scale=1,user-scalable=no"
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;800&display=swap"
      rel="stylesheet"
    />
    <style>
      body {
        margin: 0;
        padding: 0;
        font-family: "Open Sans", sans-serif;
        font-weight: 400;
        color: rgb(32, 32, 32);
        background-color: rgb(236, 232, 228);
      }

      h1 {
        font-size: 2.5rem;
        font-weight: 800;
        margin: 10px 0;
        padding: 0;
        color: rgb(0, 0, 0);
      }

      h2 {
        font-size: 1.5rem;
        font-weight: 800;
        margin: 0;
        padding: 0;
        color: rgb(75, 75, 75);
      }

      p {
        font-size: 1.1rem;
        font-weight: 400;
        margin: 0 0 15px 0;
        padding: 0;
      }

      a:link,
      a:visited {
        color: rgb(12, 73, 34);
      }

      a:hover {
        color: rgb(86, 86, 86);
        text-decoration: none;
      }

      section {
        width: 80%;
        margin: 0 auto;
      }

      footer {
        width: 80%;
        margin: 0 auto;
        color: rgb(100, 100, 100);
      }
    </style>
  </head>

  <body>
    <section>
      <h1>Hello World!</h1>
      <h2>Take a tour of Kentucky</h2>

      <iframe
        title="Mapbox area of interest"
        width="100%"
        height="576"
        src="map.html"
        frameborder="0"
        allow="fullscreen"
        allowfullscreen="true"
        mozallowfullscreen="true"
        webkitallowfullscreen="true"
      >
      </iframe>
      <p>Map shows contours around and location of Natural Bridge in Red River Gorge <a href="map.html">Enlarge map</a></p>

      <!-- 💡💡💡 Cesium map: paste embed code below -->

      <iframe
        title="Cesium area of interest"
        width="100%"
        height="576"
        src="https://cesium.com/ion/stories/viewer/?id=fcc480b1-44fb-47fb-87e9-9db73c751bf9"
        frameborder="0"
        allow="fullscreen"
        allowfullscreen="true"
        mozallowfullscreen="true"
        webkitallowfullscreen="true"
      >
      </iframe>
      <p>Going to Natural Bridge</p>

      <p>
        This map shows a fly-over of the road leading to Natural Bridge, 
        with a quick detour up the mountain to the top and over the ridge. 
        The bridge is located in Red River Gorge in the Daniel Boone National Forest. 
      </p>

      <p>
       The goal of this project is to visualize the drive through Daniel Boone National Forest with a 
       birds-eye view of Natural Bridge.
      </p>

      <img src="map1.jpg" alt="Something about this map" width="100%" />
      <p>Caption for map1</p>

      <img src="map2.jpg" alt="Something about this map" width="100%" />
      <p>Caption for map2</p>
    </section>
    <footer>
      <hr />
      <p>
        Page and visualizations created by B for GEO 409, Department of
        Geography, University of Kentucky. Spring 2022.
      </p>
      <p>
        Visualizations created from lidar data provided by
        <a href="https://kyfromabove.ky.gov/">KyFromAbove</a> in ArcGIS Pro
        and Blender. Additional sources of information from <a href="https://...">name of source</a>, April 18, 2022.
      </p>
    </footer>
  </body>
</html>
