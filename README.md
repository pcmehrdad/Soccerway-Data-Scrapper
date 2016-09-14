# Soccerway data web scrapper
<h2>Description</h2>
<p>This script can be run through command line, it will scrap data from soccreway.com and will generate an XML file with all the data and the file will get the data as name.</p>
<p>It is scrapping the <b>date,home,away,goals,season,champion,game week,url and goalers</b>.<p>
<p>The first part is the simple_html_dom.php which can be included by uncommenting this line: 
//require_once( dirname(FILE) . '/simple_html_dom.php' );</p>
<h2>Usage</h2>
<p>At the top of the script there is an array (competitions) with the URL's for scrapping.</p>
<p>Example of array: 
'AUS-BUNDESLIGA' => array('name' => 'BUNDESLIGA','region' => 'AUSTRIA','url' => 'national/austria/bundesliga/')</p>
<p>You can run it through command line.
Example: php scrap.php </p>
<p></p><p></p>
<p><b>By Karamanlis Simos</b></p>
