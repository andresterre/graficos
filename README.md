graficos
========
<!-- MotionChart generated in R 3.1.1 by googleVis 0.5.5 package -->
<!-- Mon Oct 20 12:48:57 2014 -->


<!-- jsHeader -->
<script type="text/javascript">


// jsData 
function gvisDataMotionChartID13a4172561a7 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "CACAO",
2009,
13.77 
],
[
 "ACEITE DE PALMA",
2009,
10.62 
],
[
 "SARDINA",
2009,
0.51 
],
[
 "CAMARON",
2009,
0 
],
[
 "MADERA",
2009,
4.42 
],
[
 "CONFITERIA SIN CACAO",
2009,
1.58 
],
[
 "NEUMATICOS",
2009,
0 
],
[
 "TABACO",
2009,
2.82 
],
[
 "SUETERES",
2009,
0.35 
],
[
 "ESCENCIAS DE CAFE, TE, YERBA MATE",
2009,
0.4 
],
[
 "OTROS",
2009,
8.92 
],
[
 "CACAO",
2010,
24.36 
],
[
 "ACEITE DE PALMA",
2010,
4.18 
],
[
 "SARDINA",
2010,
1.93 
],
[
 "CAMARON",
2010,
0.27 
],
[
 "MADERA",
2010,
2.66 
],
[
 "CONFITERIA SIN CACAO",
2010,
1.09 
],
[
 "NEUMATICOS",
2010,
0.46 
],
[
 "TABACO",
2010,
2.55 
],
[
 "SUETERES",
2010,
0.94 
],
[
 "ESCENCIAS DE CAFE, TE, YERBA MATE",
2010,
0.54 
],
[
 "OTROS",
2010,
12.14 
],
[
 "CACAO",
2011,
29.05 
],
[
 "ACEITE DE PALMA",
2011,
7.68 
],
[
 "SARDINA",
2011,
1.55 
],
[
 "CAMARON",
2011,
0.15 
],
[
 "MADERA",
2011,
1.28 
],
[
 "CONFITERIA SIN CACAO",
2011,
0.64 
],
[
 "NEUMATICOS",
2011,
2.79 
],
[
 "TABACO",
2011,
0.05 
],
[
 "SUETERES",
2011,
1.11 
],
[
 "ESCENCIAS DE CAFE, TE, YERBA MATE",
2011,
0.29 
],
[
 "OTROS",
2011,
9.67 
],
[
 "CACAO",
2012,
18.61 
],
[
 "ACEITE DE PALMA",
2012,
22.07 
],
[
 "SARDINA",
2012,
0.84 
],
[
 "CAMARON",
2012,
0 
],
[
 "MADERA",
2012,
2.28 
],
[
 "CONFITERIA SIN CACAO",
2012,
0.87 
],
[
 "NEUMATICOS",
2012,
0.65 
],
[
 "TABACO",
2012,
0 
],
[
 "SUETERES",
2012,
0.6 
],
[
 "ESCENCIAS DE CAFE, TE, YERBA MATE",
2012,
0.22 
],
[
 "OTROS",
2012,
9.71 
],
[
 "CACAO",
2013,
23.79 
],
[
 "ACEITE DE PALMA",
2013,
8.6 
],
[
 "SARDINA",
2013,
6.54 
],
[
 "CAMARON",
2013,
0.42 
],
[
 "MADERA",
2013,
0.95 
],
[
 "CONFITERIA SIN CACAO",
2013,
0.81 
],
[
 "NEUMATICOS",
2013,
0 
],
[
 "TABACO",
2013,
0 
],
[
 "SUETERES",
2013,
0.73 
],
[
 "ESCENCIAS DE CAFE, TE, YERBA MATE",
2013,
1.69 
],
[
 "OTROS",
2013,
10.65 
],
[
 "CACAO",
2014,
31.27 
],
[
 "ACEITE DE PALMA",
2014,
0.02 
],
[
 "SARDINA",
2014,
15.28 
],
[
 "CAMARON",
2014,
20.14 
],
[
 "MADERA",
2014,
0.78 
],
[
 "CONFITERIA SIN CACAO",
2014,
1.17 
],
[
 "NEUMATICOS",
2014,
1.92 
],
[
 "TABACO",
2014,
0 
],
[
 "SUETERES",
2014,
0.74 
],
[
 "ESCENCIAS DE CAFE, TE, YERBA MATE",
2014,
0.82 
],
[
 "OTROS",
2014,
13.88 
] 
];
data.addColumn('string','DESCRIPCION');
data.addColumn('number','A�o');
data.addColumn('number','Millones.USD_FOB');
data.addRows(datajson);
return(data);
}


// jsDrawChart
function drawChartMotionChartID13a4172561a7() {
var data = gvisDataMotionChartID13a4172561a7();
var options = {};
options["width"] =    600;
options["height"] =    500;
options["state"] = "\n+ {\"yZoomedIn\":false,\"uniColorForNonSelected\":false,\"playDuration\":15000,\"orderedByY\":false,\"yZoomedDataMax\":32,\"sizeOption\":\"_UNISIZE\",\"xAxisOption\":\"_ALPHABETICAL\",\"colorOption\":\"_UNIQUE_COLOR\",\"xZoomedDataMin\":0,\"duration\":{\"timeUnit\":\"Y\",\"multiplier\":1},\"iconType\":\"VBAR\",\"dimensions\":{\"iconDimensions\":[\"dim0\"]},\"time\":\"2009\",\"xLambda\":1,\"nonSelectedAlpha\":0.4,\"iconKeySettings\":[{\"key\":{\"dim0\":\"CAMARON\"}}],\"yLambda\":1,\"xZoomedDataMax\":11,\"xZoomedIn\":false,\"showTrails\":false,\"orderedByX\":true,\"yZoomedDataMin\":0,\"yAxisOption\":\"2\"}\n+";


    var chart = new google.visualization.MotionChart(
    document.getElementById('MotionChartID13a4172561a7')
    );
    chart.draw(data,options);
    

}
  


// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "motionchart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartMotionChartID13a4172561a7);
})();
function displayChartMotionChartID13a4172561a7() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}


// jsFooter
</script>


<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartMotionChartID13a4172561a7"></script>


<!-- divChart -->
  
<div id="MotionChartID13a4172561a7" 
  style="width: 600; height: 500;">
</div>

Gráficos elaborados por Andrés Terreros
