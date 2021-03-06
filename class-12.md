# EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS

It's easy to get started with Chart.js. All that's required is the script included in your page along with a single <canvas> node to render the chart

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>


<canvas id="buyers" width="600" height="400"></canvas> (example)

- At first sight a <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes. 
Indeed, the <canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. 
When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. 
The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas,
it will appear distorted.

- The <canvas> element differs from an <img> tag in that, like for <video>, <audio>, or <picture> elements, it is easy to define some fallback content,
to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers.
You should always provide fallback content to be displayed by those browsers.

- Providing fallback content is very straightforward: just insert the alternate content inside the <canvas> element. 
Browsers that don't support <canvas> will ignore the container and render the fallback content inside it. 
Browsers that do support <canvas> will ignore the content inside the container, and just render the canvas normally.
