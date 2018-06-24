---
title       : "Pitch Presentation"
subtitle    : "Data Products Assignment no. 3"
author      : "Jan Schubert"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
github:
    user: schubertjan
    repo: DataProducts_Assignment3
---

## What does the app do?

This app uses Google Search data to compare popularity of each cycling Grand Tour race (Tour de France, Vuelta a Espana and Giro d'Italia) around the world. 

--- .class #id

## What is a Grand Tour

In case you are not a cycling fan and don't know what a Grand Tour is here is a definition from Wikipedia: 

In road bicycle racing, a Grand Tour is one of the three major European professional cycling stage races: Tour de France, Giro d'Italia and Vuelta a España. Collectively they are termed the Grand Tours, and all three races are similar in format being multi-week races with daily stages. They have a special status in the UCI regulations: more points for the UCI World Tour are distributed in Grand Tours than in other races, and they are the only stage races allowed to last longer than 14 days.


Source: Wikipedia https://en.wikipedia.org/wiki/Grand_Tour_(cycling) 

---

## What is Google Search Index

Google provides aggregated search data in their public product called Google Trends. This provides relative frequency of a search term in a given country and worldwide.


Source: Google Trends https://trends.google.com/trends/?geo=US 

---

## Example of the app (Tour de France)

Tour de France is the biggest from the three Grand Tours and attracts interest from outside the traditional cycling regions (Europe and Columbia).

<!-- GeoChart generated in R 3.4.3 by googleVis 0.6.2 package -->
<!-- Sun Jun 24 17:15:09 2018 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartID35e86a5c2182 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
"Eritrea",
1
],
[
"France",
14
],
[
"Luxembourg",
13
],
[
"Andorra",
1
],
[
"Slovakia",
11
],
[
"Netherlands",
10
],
[
"Colombia",
10
],
[
"St Pierre & Miquelon",
1
],
[
"Belgium",
9
],
[
"Martinique",
1
],
[
"Monaco",
1
],
[
"St BarthÃ©lemy",
1
],
[
"Denmark",
8
],
[
"Guadeloupe",
1
],
[
"Isle of Man",
1
],
[
"Norway",
6
],
[
"Greenland",
1
],
[
"Guernsey",
1
],
[
"Caribbean Netherlands",
1
],
[
"Jersey",
1
],
[
"Switzerland",
5
],
[
"Portugal",
5
],
[
"Spain",
5
],
[
"Czechia",
4
],
[
"French Polynesia",
1
],
[
"French Guiana",
1
],
[
"St Martin",
1
],
[
"Bermuda",
1
],
[
"Faroe Islands",
1
],
[
"United Kingdom",
19
],
[
"RÃ©union",
1
],
[
"Gibraltar",
1
],
[
"Anguilla",
1
],
[
"Seychelles",
1
],
[
"Aruba",
1
],
[
"Mauritius",
1
],
[
"New Caledonia",
1
],
[
"San Marino",
1
],
[
"Burkina Faso",
1
],
[
"CuraÃ§ao",
1
],
[
"Slovenia",
18
],
[
"Italy",
18
],
[
"Ireland",
18
],
[
"Liechtenstein",
1
],
[
"Sint Maarten",
1
],
[
"Australia",
18
],
[
"Costa Rica",
18
],
[
"Togo",
1
],
[
"Mayotte",
1
],
[
"Cayman Islands",
1
],
[
"Germany",
17
],
[
"Cameroon",
1
],
[
"Svalbard & Jan Mayen",
1
],
[
"Belize",
1
],
[
"Djibouti",
1
],
[
"Central African Republic",
1
],
[
"Madagascar",
1
],
[
"Rwanda",
1
],
[
"Estonia",
1
],
[
"South Africa",
16
],
[
"St Helena",
1
],
[
"New Zealand",
16
],
[
"Panama",
1
],
[
"Niger",
1
],
[
"South Sudan",
1
],
[
"Turks & Caicos Islands",
1
],
[
"Austria",
15
],
[
"Iceland",
1
],
[
"Malta",
1
],
[
"Sweden",
15
],
[
"Hungary",
15
],
[
"Canada",
15
],
[
"Morocco",
15
],
[
"Ãland Islands",
1
],
[
"Congo - Brazzaville",
1
],
[
"Uruguay",
1
],
[
"Barbados",
1
],
[
"Poland",
12
],
[
"Croatia",
12
],
[
"Algeria",
12
],
[
"Gabon",
1
],
[
"Vanuatu",
1
],
[
"Tunisia",
1
],
[
"Mali",
1
],
[
"Senegal",
1
],
[
"Antigua & Barbuda",
1
],
[
"Cuba",
1
],
[
"Venezuela",
12
],
[
"CÃ´te dâIvoire",
1
],
[
"Suriname",
1
],
[
"Guyana",
1
],
[
"Finland",
12
],
[
"Romania",
12
],
[
"St Vincent & Grenadines",
1
],
[
"United States",
7
],
[
"British Virgin Islands",
1
],
[
"St Lucia",
1
],
[
"Ethiopia",
1
],
[
"Burundi",
1
],
[
"Israel",
7
],
[
"Namibia",
1
],
[
"Chad",
1
],
[
"Benin",
1
],
[
"Congo - Kinshasa",
1
],
[
"Guatemala",
1
],
[
"Cape Verde",
1
],
[
"Serbia",
7
],
[
"Albania",
1
],
[
"US Virgin Islands",
1
],
[
"Angola",
1
],
[
"Macedonia (FYROM)",
1
],
[
"Botswana",
1
],
[
"Cyprus",
1
],
[
"Chile",
7
],
[
"Guinea",
1
],
[
"Ecuador",
7
],
[
"Mauritania",
1
],
[
"Bulgaria",
7
],
[
"Argentina",
7
],
[
"Greece",
7
],
[
"Trinidad & Tobago",
1
],
[
"Montenegro",
1
],
[
"Japan",
7
],
[
"Nicaragua",
1
],
[
"Bosnia & Herzegovina",
1
],
[
"Puerto Rico",
1
],
[
"Latvia",
1
],
[
"Dominican Republic",
1
],
[
"Honduras",
1
],
[
"Singapore",
7
],
[
"Bahamas",
1
],
[
"Hong Kong",
1
],
[
"Mexico",
3
],
[
"Afghanistan",
1
],
[
"El Salvador",
1
],
[
"Guam",
1
],
[
"Grenada",
1
],
[
"Paraguay",
1
],
[
"United Arab Emirates",
1
],
[
"Macau",
1
],
[
"Swaziland",
1
],
[
"China",
1
],
[
"Qatar",
1
],
[
"Brunei",
1
],
[
"Lithuania",
1
],
[
"Uganda",
1
],
[
"Kazakhstan",
1
],
[
"Haiti",
1
],
[
"Zimbabwe",
1
],
[
"Maldives",
1
],
[
"Taiwan",
3
],
[
"St Kitts & Nevis",
1
],
[
"Jamaica",
1
],
[
"Dominica",
1
],
[
"Philippines",
3
],
[
"Western Sahara",
1
],
[
"Bhutan",
1
],
[
"Peru",
1
],
[
"Sri Lanka",
1
],
[
"Lebanon",
1
],
[
"Zambia",
1
],
[
"Fiji",
1
],
[
"Lesotho",
1
],
[
"Mozambique",
1
],
[
"Malawi",
1
],
[
"Thailand",
3
],
[
"Cambodia",
1
],
[
"Bahrain",
1
],
[
"South Korea",
1
],
[
"Sierra Leone",
1
],
[
"Kosovo",
1
],
[
"Bolivia",
1
],
[
"Kenya",
1
],
[
"Malaysia",
1
],
[
"Belarus",
1
],
[
"Gambia",
1
],
[
"Brazil",
3
],
[
"Ukraine",
3
],
[
"Moldova",
1
],
[
"Oman",
1
],
[
"Sudan",
1
],
[
"Papua New Guinea",
1
],
[
"Myanmar (Burma)",
1
],
[
"Nepal",
1
],
[
"Mongolia",
1
],
[
"Russia",
2
],
[
"Georgia",
1
],
[
"Saudi Arabia",
1
],
[
"Laos",
1
],
[
"Palestine",
1
],
[
"Kuwait",
1
],
[
"Yemen",
1
],
[
"Kyrgyzstan",
1
],
[
"Tanzania",
1
],
[
"Ghana",
1
],
[
"Syria",
1
],
[
"Libya",
1
],
[
"Nigeria",
1
],
[
"Jordan",
1
],
[
"Iraq",
1
],
[
"Turkmenistan",
1
],
[
"Turkey",
2
],
[
"Uzbekistan",
1
],
[
"Indonesia",
2
],
[
"Iran",
1
],
[
"Armenia",
1
],
[
"Egypt",
1
],
[
"India",
2
],
[
"Somalia",
1
],
[
"Azerbaijan",
1
],
[
"Bangladesh",
1
],
[
"Pakistan",
1
],
[
"Vietnam",
1
],
[
"Wallis & Futuna",
1
],
[
"British Indian Ocean Territory",
1
],
[
"Montserrat",
1
],
[
"Falkland Islands (Islas Malvinas)",
1
],
[
"Cook Islands",
1
],
[
"Guinea-Bissau",
1
],
[
"Equatorial Guinea",
1
],
[
"Comoros",
1
],
[
"Northern Mariana Islands",
1
],
[
"Marshall Islands",
1
],
[
"Timor-Leste",
1
],
[
"American Samoa",
1
],
[
"Samoa",
1
],
[
"Solomon Islands",
1
],
[
"Liberia",
1
],
[
"Tajikistan",
1
],
[
"Antarctica",
1
],
[
"French Southern Territories",
1
],
[
"Bouvet Island",
1
],
[
"Cocos (Keeling) Islands",
1
],
[
"Christmas Island",
1
],
[
"Micronesia",
1
],
[
"Heard & McDonald Islands",
1
],
[
"Kiribati",
1
],
[
"Norfolk Island",
1
],
[
"Niue",
1
],
[
"Nauru",
1
],
[
"Pitcairn Islands",
1
],
[
"Palau",
1
],
[
"North Korea",
1
],
[
"South Georgia & South Sandwich Islands",
1
],
[
"SÃ£o TomÃ© & PrÃ­ncipe",
1
],
[
"Tokelau",
1
],
[
"Tonga",
1
],
[
"Tuvalu",
1
],
[
"US Outlying Islands",
1
],
[
"Vatican City",
1
] 
];
data.addColumn('string','country');
data.addColumn('number','index');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoChartID35e86a5c2182() {
var data = gvisDataGeoChartID35e86a5c2182();
var options = {};
options["width"] = 556;
options["height"] = 347;

    var chart = new google.visualization.GeoChart(
    document.getElementById('GeoChartID35e86a5c2182')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "geochart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartGeoChartID35e86a5c2182);
})();
function displayChartGeoChartID35e86a5c2182() {
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
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartID35e86a5c2182"></script>
 
<!-- divChart -->
  
<div id="GeoChartID35e86a5c2182" 
  style="width: 556; height: 347;">
</div>

---

## Thanks!

Explore how popular are other Grand Tours in your country in the app here  https://schubertjan.shinyapps.io/Assignment3/ 

Don't forget to tune in to this year's Tour de France which starts on July 7 :)





