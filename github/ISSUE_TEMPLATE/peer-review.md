<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1"/>
    <title>README - Queen’s Student Page</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        margin: 2rem;
        color: #222;
      }
      h1, h2 {
        color: #00274C; /* Queen's blue */
      }
      code {
        background: #f4f4f4;
        padding: 2px 4px;
        border-radius: 4px;
      }
      pre {
        background: #f4f4f4;
        padding: 10px;
        border-radius: 6px;
        overflow-x: auto;
      }
    </style>
  </head>
  <body>
    <h1>Queen’s Student Page — README</h1>

    <h2>How to Update</h2>
    <ul>
      <li>Edit <code>index.html</code> to update your name, about section, and list of courses.</li>
      <li>Add new images in the root folder (example: <code>me.jpg</code>) and update the <code>&lt;img src="..."&gt;</code> path.</li>
      <li>Always include an <code>alt</code> attribute for accessibility.</li>
      <li>Make design changes in <code>style.css</code> (avoid inline CSS inside <code>index.html</code>).</li>
    </ul>

    <h2>Deployment</h2>
    <p>
      Push changes to the <code>main</code> branch. GitHub Pages will update automatically and serve the site at:
      <br/>
      <strong>https://username.github.io/queens-student-page/</strong>
    </p>

    <h2>Tips</h2>
    <ul>
      <li>Keep hero images ~200–400 KB for faster loading.</li>
      <li>Commit messages should explain <em>why</em> a change was made (not just “update”).</li>
      <li>Check functionality: open live site, click every link, and confirm images load.</li>
    </ul>
  </body>
</html>
