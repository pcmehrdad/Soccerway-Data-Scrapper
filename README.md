# Soccerway data web scrapper
<h2>Description</h2>
<p>This script can be run through command line, it will scrap data from soccreway.com and will generate an XML file with all the data and the file will get the date as name.</p>
<p>It is scrapping the following data from each game:
<b><ul><li>date</li><li>home</li><li>away</li><li>goals</li><li>season</li><li>champion</li><li>region</li><li>game week</li><li>game url</li><li>champion url</li><li>region url</li><li>goalers</li></ul></b><p>
<p>The first part is the simple_html_dom.php which can be included by uncommenting this line: 
//require_once( dirname(FILE) . '/simple_html_dom.php' );</p>
![Alt text](https://raw.githubusercontent.com/skaramanlis/Soccerway-Data-Scrapper/master/Screenshot_2.png "XML example")
<h2>Usage</h2>
<p>At the top of the script there is an array (competitions) with the URL's for scrapping.</p>
<p>Example of array: 
'AUS-BUNDESLIGA' => array('name' => 'BUNDESLIGA','region' => 'AUSTRIA','url' => 'national/austria/bundesliga/')</p>
<p>You can run it through command line.
Example: php scrap.php </p>
<p></p><p></p>
<p><b>By Karamanlis Simos</b></p>
