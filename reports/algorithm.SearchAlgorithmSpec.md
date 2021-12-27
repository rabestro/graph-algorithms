<!DOCTYPE html><html>
<head>
<meta http-equiv='Content-Type' content='text/html; charset=utf-8'></meta>
<style>body {
  font-family: Helvetica, Arial, sans-serif;
  font-weight: 300;
}

h2 {
  font-weight: 400;
}

h3 {
  font-weight: 200;
}

.back-link {
  font-size: small;
}

table {
  margin: 5px;
}

div.date-test-ran {
  font-size: small;
  font-style: italic;
}

table.features-table {
  width: 800px;
}

table.summary-table {
  width: 800px;
  text-align: left;
  font-weight: bold;
  font-size: small;
}

table.summary-table th {
  background: lightblue;
  padding: 6px;
}

table.summary-table td {
  background: #E0E0E0;
  padding: 6px;
}

pre.title {
  font-family: inherit;
  font-size: 24px;
  line-height: 28px;
  letter-spacing: -1px;
  color: #333;
}

pre.narrative {
  font-family: inherit;
  font-size: 18px;
  font-style: italic;
  line-height: 23px;
  letter-spacing: -1px;
  color: #333;
}

.feature-description {
  font-size: large;
  background: lightblue;
  padding: 12px;
}

.feature-toc-error {
  color: #F89A4F;
}

.feature-toc-failure {
  color: #FF8080;
}

.feature-toc-ignored {
  color: lightgray;
}

.feature-toc-pass {
  color: green;
}

.feature-description.error {
  background: #F89A4F;
}

.feature-description.failure {
  background: #FF8080;
}

.feature-description.ignored {
  background: lightgray;
}

.feature-description.ignored .reason {
  color: black;
  font-style: italic;
  font-size: small;
}

div.extra-info {
  font-size: small;
}

div.spec-headers {
  margin: 4px;
  font-style: italic;
}

div.spec-header {
}

div.issues {
  margin-top: 6px;
  padding: 10px 5px 5px 5px;
  background-color: lemonchiffon;
  color: black;
  font-weight: 500;
  font-size: small;
  max-width: 50%;
}

div.pending-feature {
  background-color: dodgerblue;
  color: white;
  margin-top: 6px;
  padding: 5px;
  text-align: center;
  font-size: small;
  max-width: 120px;
}

div.problem-description {
  padding: 10px;
  background: pink;
  border-radius: 10px;
}

div.problem-header {
  font-weight: bold;
  color: red;
}

div.problem-list {

}

table.ex-table th {
  background: lightblue;
  padding: 5px;
}

table.ex-table td {
  background: #E0E0E0;
  padding: 2px 5px 2px 5px;
}

table td {
  min-width: 50px;
}

col.block-kind-col {
  width: 70px;
}

span.spec-header {
  font-weight: bold;
}

div.spec-text {
  /*color: green;*/
}

div.spec-status {
  font-style: italic;
}

.ignored {
  color: gray;
}

td.ex-result {
  text-align: center;
  background: white !important;
}

.ex-pass {
  color: darkgreen;
}

.ex-fail {
  color: red;
  font-weight: bold;
}

div.block-kind {
  margin: 2px;
  font-style: italic;
}

div.block-text {

}

pre.block-source {
  background-color: whitesmoke;
  padding: 10px;
}

pre.block-source.error {
  background-color: pink;
  color: red;
  font-weight: bold;
}

pre.block-source.pre-error {

}

pre.block-source.before-error {
  margin-bottom: -14px;
}

pre.block-source.after-error {
  color: gray;
  margin-top: -14px;
}

pre.block-source.post-error {
  color: gray;
}

div.footer {
  text-align: center;
  font-size: small;
}
</style>
</head>
<body>
<h2>Report for algorithm.SearchAlgorithmSpec</h2>
<hr></hr>
<div class='back-link'>
<a href='index.html'>&lt;&lt; Back</a>
</div>
<div class='summary-report'>
<h3>Summary:</h3>
<div class='date-test-ran'>Created on Mon Dec 27 21:30:57 EET 2021 by rabes</div>
<table class='summary-table'>
<thead>
<tr>
<th>Executed features</th>
<th>Passed</th>
<th>Failures</th>
<th>Errors</th>
<th>Skipped</th>
<th>Success rate</th>
<th>Time</th>
</tr>
</thead>
<tbody>
<tr>
<td>1</td>
<td>1</td>
<td>0</td>
<td>0</td>
<td>0</td>
<td>100.0%</td>
<td>0.162 seconds</td>
</tr>
</tbody>
</table>
</div>
<pre class='title'>Comparison of two algorithms</pre>
<h3>Features:</h3>
<table class='features-table'>
<colgroup>
<col class='block-kind-col'></col>
<col class='block-text-col'></col>
</colgroup>
<tbody>
<ul id='toc'>
<li>
<a href='#-1278284136' class='feature-toc-pass'>should find a route for a complex graph</a>
</li>
</ul>
<tr>
<td colspan='10'>
<div class='feature-description' id='-1278284136'>
<span>should find a route for a complex graph</span>
<span style='float: right; font-size: 60%;'>
<a href='#toc'>Return</a>
</span>
<div class='issues'>
<div>Issues:</div>
<ul>
<li>
<a href='https://github.com/rabestro/graph-search-algorithm-java/blob/master/docs/complex.gif'>complex.gif</a>
</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class='block-kind'>Given:</div>
</td>
<td>
<div class='block-text'>A complex graph sample</div>
</td>
</tr>
<tr>
<td>
<div class='block-kind'>When:</div>
</td>
<td>
<div class='block-text'>we use Breadth First Search algorithm for the first route</div>
</td>
</tr>
<tr>
<td>
<div class='block-kind'>And:</div>
</td>
<td>
<div class='block-text'>we use Dijkstras algorithm for the second route</div>
</td>
</tr>
<tr>
<td>
<div class='block-kind'>Then:</div>
</td>
<td>
<div class='block-text'>the first route is the shortest</div>
</td>
</tr>
<tr>
<td>
<div class='block-kind'>And:</div>
</td>
<td>
<div class='block-text'>the second route is the fastest</div>
</td>
</tr>
<tr>
<td>
<div class='block-kind'>And:</div>
</td>
<td>
<div class='block-text'>the distance calculated correctly</div>
</td>
</tr>
<tr>
<td>
<div class='block-kind'>Where:</div>
</td>
<td>
<div class='block-text'>----</div>
</td>
</tr>
<tr>
<td>
<div class='block-kind'>Examples:</div>
</td>
<td>
<div class='spec-examples'>
<table class='ex-table'>
<thead>
<tr>
<th class='ex-header'>source</th>
<th class='ex-header'>target</th>
<th class='ex-header'>d1</th>
<th class='ex-header'>shortest</th>
<th class='ex-header'>d2</th>
<th class='ex-header'>fastest</th>
</tr>
</thead>
<tbody>
<tr class='ex-pass'>
<td class='ex-value'>A</td>
<td class='ex-value'>A</td>
<td class='ex-value'>0</td>
<td class='ex-value'>[A]</td>
<td class='ex-value'>0</td>
<td class='ex-value'>[A]</td>
<td class='ex-result'>OK</td>
</tr>
<tr class='ex-pass'>
<td class='ex-value'>B</td>
<td class='ex-value'>B</td>
<td class='ex-value'>0</td>
<td class='ex-value'>[B]</td>
<td class='ex-value'>0</td>
<td class='ex-value'>[B]</td>
<td class='ex-result'>OK</td>
</tr>
<tr class='ex-pass'>
<td class='ex-value'>A</td>
<td class='ex-value'>B</td>
<td class='ex-value'>5</td>
<td class='ex-value'>[A, B]</td>
<td class='ex-value'>5</td>
<td class='ex-value'>[A, B]</td>
<td class='ex-result'>OK</td>
</tr>
<tr class='ex-pass'>
<td class='ex-value'>B</td>
<td class='ex-value'>A</td>
<td class='ex-value'>5</td>
<td class='ex-value'>[B, A]</td>
<td class='ex-value'>5</td>
<td class='ex-value'>[B, A]</td>
<td class='ex-result'>OK</td>
</tr>
<tr class='ex-pass'>
<td class='ex-value'>A</td>
<td class='ex-value'>C</td>
<td class='ex-value'>12</td>
<td class='ex-value'>[A, B, C]</td>
<td class='ex-value'>9</td>
<td class='ex-value'>[A, H, G, C]</td>
<td class='ex-result'>OK</td>
</tr>
<tr class='ex-pass'>
<td class='ex-value'>C</td>
<td class='ex-value'>A</td>
<td class='ex-value'>12</td>
<td class='ex-value'>[C, B, A]</td>
<td class='ex-value'>12</td>
<td class='ex-value'>[C, B, A]</td>
<td class='ex-result'>OK</td>
</tr>
<tr class='ex-pass'>
<td class='ex-value'>A</td>
<td class='ex-value'>G</td>
<td class='ex-value'>5</td>
<td class='ex-value'>[A, H, G]</td>
<td class='ex-value'>5</td>
<td class='ex-value'>[A, H, G]</td>
<td class='ex-result'>OK</td>
</tr>
<tr class='ex-pass'>
<td class='ex-value'>C</td>
<td class='ex-value'>D</td>
<td class='ex-value'>3</td>
<td class='ex-value'>[C, D]</td>
<td class='ex-value'>3</td>
<td class='ex-value'>[C, D]</td>
<td class='ex-result'>OK</td>
</tr>
<tr class='ex-pass'>
<td class='ex-value'>D</td>
<td class='ex-value'>C</td>
<td class='ex-value'>20</td>
<td class='ex-value'>[D, C]</td>
<td class='ex-value'>19</td>
<td class='ex-value'>[D, E, F, G, C]</td>
<td class='ex-result'>OK</td>
</tr>
<tr class='ex-pass'>
<td class='ex-value'>B</td>
<td class='ex-value'>D</td>
<td class='ex-value'>10</td>
<td class='ex-value'>[B, C, D]</td>
<td class='ex-value'>10</td>
<td class='ex-value'>[B, C, D]</td>
<td class='ex-result'>OK</td>
</tr>
<tr class='ex-pass'>
<td class='ex-value'>D</td>
<td class='ex-value'>B</td>
<td class='ex-value'>27</td>
<td class='ex-value'>[D, C, B]</td>
<td class='ex-value'>26</td>
<td class='ex-value'>[D, E, F, G, C, B]</td>
<td class='ex-result'>OK</td>
</tr>
<tr class='ex-pass'>
<td class='ex-value'>D</td>
<td class='ex-value'>H</td>
<td class='ex-value'>34</td>
<td class='ex-value'>[D, C, B, A, H]</td>
<td class='ex-value'>33</td>
<td class='ex-value'>[D, E, F, G, C, B, A, H]</td>
<td class='ex-result'>OK</td>
</tr>
</tbody>
</table>
</div>
</td>
<td>
<div class='spec-status'>12/12 passed</div>
</td>
</tr>
</tbody>
</table>
<hr></hr>
<div class='footer'>Generated by <a href='https://github.com/renatoathaydes/spock-reports'>Athaydes Spock Reports</a></div>
</body>
</html>