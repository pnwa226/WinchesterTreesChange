<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8" />
  <title>Presentation</title>
  <meta name="viewport" content="initial-scale=1,maximum-scale=1,user-scalable=no" />
 <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">

  <style>
    /* Set margin/padding to fit border in box model */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    /* Define styles on body (and all descendants) */
    body {
      margin: 0;
      padding: 0;
      font-family: "Open Sans", sans-serif;
      font-weight: 400;
      color: rgb(32, 32, 32);
      background-color: rgb(236, 232, 228);
    }
    .bebasfont {
  font-family: "Bebas Neue", sans-serif;
  font-weight: 400;
  font-style: normal;
}

}
    /* Define styles for the headings */
    h1 {
      font-size: 3rem;
      font-weight: 800;
      margin: 10px 0;
      padding: 0;
      color: hsl(240, 37%, 33%);
    }

    h2 {
      font-size: 2rem;
      font-weight: 800;
      margin: 0;
      padding: 0;
    }


    h3 {
      font-size: 1.5rem;
      font-weight: bold;
      margin-bottom: 10px;
    }

    /* Define styles for the paragraph */
    p {
      font-size: 1.3rem;
      font-weight: 400;
      margin: 0 0 10px 0;
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

    iframe {
      border: 1px solid rgb(200, 200, 200);
      border-radius: 10px;
      margin-top: 20px;
    }

    .caption {
      font-size: 0.8rem;
      font-weight: 400;
      font-style: italic;
      margin: 0;
      padding: 0;
      color: rgb(100, 100, 100);
    }

    .title {
      text-align: left;
      margin: 20px;
    }

    /* Set up a container for the two columns */
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }

    /* Define styles for the left column */
    .left-column {
      flex-basis: 40%;
      padding: 20px;
      margin-bottom: 20px;
    }

    /* Define styles for the right column */
    .right-column {
      flex-basis: 55%;
      background-color: rgba(255, 255, 255, 0.35);
      border-radius: 10px;
      padding: 20px;
      margin-bottom: 20px;
    }

    /* Round image corners for images inside the right-column */
    .right-column img {
      border-radius: 10px;
    }

    /* Media query for small screens */
    /* For screens up to 768px, apply these rules. */
    @media (max-width: 768px) {

      /* Change to a single column layout */
      .container {
        flex-direction: column;
      }

      /* Set full width for both columns */
      .left-column,
      .right-column {
        flex-basis: 100%;
      }
    }
  </style>
</head>

<body>
  <section>
    <!-- 💡💡💡 Cesium map: paste embed code below -->
    <iframe title="Winchester Trees" width="1024" height="576" src="https://ion.cesium.com/stories/viewer/?id=03f5fe58-07ee-447b-9f5c-4b277db6e424" frameborder="0" allow="fullscreen" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

    </iframe>
    <!-- 💡💡💡 Cesium map: paste embed code above -->
    <p class="caption">This Celsium Map gives a point cloud visualization of the streetscape trees in Winchester, KY. Point cloud data derived from kyfromabove (Phase 2)</p>
    <div class="title">
      <h1 class=".bebasfont"> This is where the title goes</h1>
      <h2>When and were of the map</h2>
    </div>
    <div class="container">
      <div class="left-column">
        <h3>Left Column - Description</h3>
        <p>
          Two sentences about your area/theme of interest (e.g., when was it
          established, created, where is it, what is unique about, etc.)
        </p>

        <p>
          Two sentences about the goals of the project (e.g., The goal of this
          project is to measure and visualize the historic entrance to Mammoth
          Cave).
        </p>

        <p>
          Visualizations created from lidar data provided by
          <a href="https://kyfromabove.ky.gov/">KyFromAbove</a> in ArcGIS Pro and
          Blender. Additional sources of information from
          <a href="https://...">name of source</a>, April, 2023.
        </p>

        <p>
          Page and visualizations created by B for GEO 409, Department of
          Geography, University of Kentucky. Spring 2024.
        </p>


      </div>
      <div class="right-column">
        <h3>Right Column - Vizualizations </h3>
        <img src="summit change.jpg" alt="Something about this map" width="75%" />
        <p class="caption">Caption for map1</p>
        <iframe width="75%" height="315" src="https://www.youtube.com/embed/nEA7Sb9RhyY?si=i1PNd6CQlMmyb8Uv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
      </div>
    </div>
  </section>
  <footer>
    <hr />
    <img src="logo-color-400px.png" alt="UKy Arts and Sciences  " width="300px">

  </footer>
</body>

</html>
