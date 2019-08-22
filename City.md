# My first wed i do
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
h1{
text-align:center;
}
body {
  font-family: Arial, Helvetica, sans-serif;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333333;
}

li {
  float: center;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 41px;
  text-decoration: none;
}

li a:hover {
  background-color: #111111;
}
/* Style the header */
header {
  background-color: #666;
  padding: 40px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
float:left;
width:30%;
heigth:300px;
}

/* Style the list inside the menu */


article {
  float: left;
  padding:20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
  overflow: scroll;
}

/* Clear floats after the columns */
section:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}
input:active{background-color: #b3d4fc;}
input:focus{background-color: #b3d4fc;}
/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>

<h2>CSS Layout Float</h2>
<p>In this example, we have created a header, two columns/boxes and a footer. On smaller screens, the columns will stack on top of each other.</p>
<p>Resize the browser window to see the responsive effect (you will learn more about this in our next chapter - HTML Responsive.)</p>

<header>
  <h2>Cities</h2>
</header>

<section>
<nav>
    <ul>
      <li><a href="#London" onclick="Myfunction()">London</a></li>
      <li><a href="#Paris" onclick="MyDemo()">Paris</a></li>
      <li><a href="#Tokyo" onclick="Mydemo()">Tokyo</a></li>
    </ul>
    </nav>
<article><p id="Ex"></p>
  <h1>Click on the city to know information about city you want</h1>
<title>
    <h1>London</h1>
    <p>London is the capital city of England. It is the most populous city in the  United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
    <p>Standing on the River Thames, London has been a major settlement for two millennia, its history going back to its founding by the Romans, who named it Londinium.</p>
    <p>London has a diverse range of people and cultures, and more than 300 languages are spoken in the region.[52] Its estimated mid-2018 municipal population (corresponding to Greater London) was 8,908,081,[4] the most populous of any city in the European Union[53] and accounting for 13.4% of the UK population.[54] London's urban area is the second most populous in the EU, after Paris, with 9,787,426 inhabitants at the 2011 census.[55] The population within the London commuter belt is the most populous in the EU with 14,040,163 inhabitants in 2016.[note 4][3][56] London was the world's most populous city from c. 1831 to 1925.[57]</p>
    <p>London contains four World Heritage Sites: the Tower of London; Kew Gardens; the site comprising the Palace of Westminster, Westminster Abbey, and St Margaret's Church; and the historic settlement in Greenwich where the Royal Observatory, Greenwich defines the Prime Meridian, 0° longitude, and Greenwich Mean Time.[58] Other landmarks include Buckingham Palace, the London Eye, Piccadilly Circus, St Paul's Cathedral, Tower Bridge, Trafalgar Square and The Shard. London has numerous museums, galleries, libraries and sporting events. These include the British Museum, National Gallery, Natural History Museum, Tate Modern, British Library and West End theatres.[59] The London Underground is the oldest underground railway network in the world.</p>
</title>
<title>
    <h1>Paris</h1>
    <p>Paris is the capital and most populous city of France, with an area of 105 square kilometres (41 square miles) and an official estimated population of 2,140,526 residents as of 1 January 2019. </p>
    <p>Paris has been one of Europe's major centres of finance, diplomacy, commerce, fashion, science, and the arts. The City of Paris is the centre and seat of government of the Île-de-France, or Paris Region, which has an estimated official 2019 population of 12,213,364, or about 18 percent of the population of France.</p>
    <p>Paris is especially known for its museums and architectural landmarks: the Louvre was the most visited art museum in the world in 2018, with 10.2 million visitors.[10][11] The Musée d'Orsay and Musée de l'Orangerie are noted for their collections of French Impressionist art, and the Pompidou Centre Musée National d'Art Moderne has the largest collection of modern and contemporary art in Europe. The historical district along the Seine in the city centre is classified as a UNESCO Heritage Site. Popular landmarks in the centre of the city include the Cathedral of Notre Dame de Paris and the Gothic royal chapel of Sainte-Chapelle, both on the Île de la Cité; the Eiffel Tower, constructed for the Paris Universal Exposition of 1889; the Grand Palais and Petit Palais, built for the Paris Universal Exposition of 1900; the Arc de Triomphe on the Champs-Élysées, and the Basilica of Sacré-Coeur on the hill of Montmartre. Paris received 23 million visitors in 2017, measured by hotel stays, with the largest numbers of foreign visitors coming from the United States, the United Kingdom, Germany and China.[12][13] It was ranked as the third most visited travel destination in the world in 2017, after Bangkok and London.[14]</p>
</title>
<title>
    <h1>Tokyo</h1>
    <p>Tokyo, the capital of Japan, is one of the largest cities of the world with a population of 12.64-million and is the biggest of the 47 prefectures throughout Japan.</p>
    <p> Its long history of prosperity started with the establishment of the Shogunate by Tokugawa Ieyasu in 1603. At that time, Tokyo was called Edo, which by the 18th century had grown to a huge city of over a million people.The 23 Special Wards of Tokyo were formerly Tokyo City. On July 1, 1943, it merged with Tokyo Prefecture and became Tokyo Metropolis with an additional 26 municipalities in the western part of the prefecture, and the Izu islands and Ogasawara islands south of Tokyo. As of October 1, 2015, the population of Tokyo is estimated to be over 13.4 million, or about 11% of Japan's total population.[12] The latest estimate in 2019 shows the growing population of Tokyo with 13.9 million people, with the special wards 9.6 million, the Tama area 4.2 million, and the Islands 25,147.[13] The prefecture is part of the world's most populous metropolitan area called the Greater Tokyo Area with over 38 million people[3] and the world's largest urban agglomeration economy. As of 2011, Tokyo hosted 51 of the Fortune Global 500 companies, the highest number of any city in the world at that time.[14] Tokyo ranked third (twice) in the International Financial Centres Development Index.[citation needed] The city is home to various television networks such as Fuji TV, Tokyo MX, TV Tokyo, TV Asahi, Nippon Television, NHK and the Tokyo Broadcasting System.</p>

</title>
</article>
<script>
function Myfunction(){
var x=document.getElementsByTagName("title")[0].text;
	document.getElementById("Ex").innerHTML=x;
}
function MyDemo(){
var x=document.getElementsByTagName("title")[1].text;
	document.getElementById("Ex").innerHTML=x;
}
function Mydemo(){
var x=document.getElementsByTagName("title")[2].text;
	document.getElementById("Ex").innerHTML=x;
}
</script>
</section>
<footer>
  <p>Footer</p>
</footer>
</form>
</body>
</html>

