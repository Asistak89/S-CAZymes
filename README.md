<html>
<head>
	<title>S-CAZymes - Home</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
	<style>
		 /* Remove the navbar's default margin-bottom and rounded borders */ 
			.navbar {
			  margin-bottom: 0;
			  border-radius: 0;
			}
			
			/* Set height of the grid so .sidenav can be 100% (adjust as needed) */
			.row.content {height: 150px}
			
			/* Set gray background color and 100% height */
			.sidenav {
			  padding-top: 20px;
			  background-color: #000000;
			  height: 350px;
			}
			.rightnav{
				height: 350px;
				overflow: scroll;
			}
			#plant-cells-id .plant-cells {
				display: none;  /* applies to every ul */
			}

			#plant-cells-id .plant-cells:first-child {
				display: block; /* limits the scope of the previous rule */
			}
	 </style>
</head>
<body a link="black" vlink = "black">
	<center><h1><font face="garamond"><b><font color="blue"><font size="6">S-CAZymes:Search-Carbohydrate active enzymes</h1></center></font></b>
	<!--Menu goes here -->
<nav class="navbar navbar-inverse">
	<div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li style="font-size:30px" class="active"><a href="Plant_cell-wall_components.html">PCW-DE</a></li>
        <li style="font-size:20px"><a href="Search_CAZyme_CAZy-classes.html">S-CAZymes</a></li>
		<li style="font-size:20px"><a href="E.C_activities_of_CBM.html">E.A's Exhibited by CBM Domains</a></li>
      </ul>
    </div>
  </div>
</nav>
  
<div class="container-fluid text-center">
	<div class="row content">    
    <div class="col-sm-10 text-left"> 
      <h3><font color="black"><b><u>Plant Cell-wall Components-Degrading Enzymes (PCW-DE):</font></b></u></h3>
      <p>Plant cells are protected with three layers known as middle lamella, primary and secondary cell walls which are made up of carbohydrates (cellulose, hemicellulose and pectin) and lignin. Plant cell walls were also found to contain lesser amounts of starch and inulin. For more information about the architecture of plant cell wall and its components and its commercial applications please find the articles cited [1-6].</p>
</div>	
  </div>
  <div class="row content">
    <div class="col-sm-2 sidenav">
		<ul class="nav nav-pills nav-stacked">
		<li style="font-size:20px"><a href="#" onclick='show_selected_cell("Cellulose")'>Cellulose</a></li>
		<li style="font-size:20px"><a href="#" onclick='show_selected_cell("Hemicellulose")'>Hemicellulose</a></li>
		<li style="font-size:20px"><a href="#" onclick='show_selected_cell("Lignin")'>Lignin</a></li>
		<li style="font-size:20px"><a href="#" onclick='show_selected_cell("Pectin")'>Pectin</a></li>
		<li style="font-size:20px"><a href="#" onclick='show_selected_cell("Starch")'>Starch</a></li>
		<li style="font-size:20px"><a href="#" onclick='show_selected_cell("Inulin")'>Inulin</a></li> 
		</ul>
    </div>
    <div class="col-sm-10 text-left rightnav" id="plant-cells-id"> 
      <div class="plant-cells" id="Cellulose">
			<h1><b><u>Cellulose</h1></b></u>
			<div class="table-responsive">    
				<table class="table table-striped">
					<thead>
					<tr>
						<td style=min-width:50px><b><u>CAZymes</b></u></td>
						<td style=min-width:50px><b><u>CAZy Class</b></u></td>
					</tr>
					</thead>
					<tbody>
					<tr>
						<td style=min-width:50px>Endo-β-1,4-glucanase / cellulase</td>
						<td style=min-width:50px>GH5; GH6; GH7; GH8; GH9; GH10; GH12; GH26; GH44; GH45; GH48; GH51; GH74; GH124</td>
					</tr>
					<tr>
						<td style=min-width:50px>β-glucosidase</td>
						<td style=min-width:50px>GH1; GH2; GH3; GH5; GH9; GH30; GH39; GH116</td>
					</tr>
					<tr>
						<td style=min-width:50px>Cellulose β-1,4-cellobiosidase</td>
						<td style=min-width:50px>GH5; GH6; GH9</td>
					</tr>
					<tr>
						<td style=min-width:50px>LPMO</td>
						<td style=min-width:50px>AA9; AA10; AA15</td>
					</tr>
					<tr>
						<td style=min-width:50px>Cellobiose dehydrogenase </td>
						<td style=min-width:50px>AA3</td>
					</tr>
					<tr>
						<td style=min-width:50px>GMC-Oxidoreductases</td>
						<td style=min-width:50px>AA3</td>
					</tr>
					<tr>
						<td style=min-width:50px>Exo-β-1,4-glucanase / cellodextrinase</td>
						<td style=min-width:50px>GH1; GH3; GH5; GH9</td>
					</tr>
					<tr>
						<td style=min-width:50px>Cellulose binding domain</td>
						<td style=min-width:50px>CBM1; CBM2; CBM3; CBM4; CBM6; CBM8; CBM9; CBM10; CBM11; CBM16; CBM17; CBM28;  CBM30; CBM37; CBM44; CBM46; CBM49; CBM59; CBM62; CBM63; CBM64; CBM65; CBM72</td>
					</tr>
					</tbody>
				</table>
				</div>
	  </div>
	  <div class="plant-cells" id="Hemicellulose">
			<<h1><b><u>Hemicellulose</h1></b></u>
			<div class="table-responsive">    
				<table class="table table-striped">
					<tr>
						<td style=min-width:50px><b><u>CAZymes</b></u></td>
						<td style=min-width:50px><b><u>CAZy Class</b></u></td>
					</tr>
					<tr>
						<td style=min-width:50px>Endo-β-1,4-xylanase</td>
						<td style=min-width:50px>GH3; GH5; GH8; GH9; GH10; GH11; GH12; GH16; GH26; GH30; GH43; GH44; GH51; GH62; GH98; GH141</td>
					</tr>
					<tr>
						<td style=min-width:50px>β-glucosidase</td>
						<td style=min-width:50px>GH1; GH2; GH3; GH5; GH9; GH30; GH39; GH116</td>
					</tr>
					<tr>
						<td style=min-width:50px>β-mannosidase</td>
						<td style=min-width:50px>GH1; GH2; GH5</td>
					</tr>
					<tr>
						<td style=min-width:50px>β-xylosidase</td>
						<td style=min-width:50px>GH1; GH3; GH5; GH30; GH39; GH43; GH51; GH52; GH54; GH116; GH120</td>
					</tr>
					<tr>
						<td style=min-width:50px>Glucan β-1,3-glucosidase</td>
						<td style=min-width:50px>GH3; GH5; GH16; GH17; GH55</td>
					</tr>
					<tr>
						<td style=min-width:50px>Mannan endo-β-1,4-mannosidase</td>
						<td style=min-width:50px>GH5; GH9; GH26; GH44; GH113; GH134</td>
					</tr>
					<tr>
						<td style=min-width:50px>α-L-arabinofuranosidase</td>
						<td style=min-width:50px>GH2; GH3; GH43; GH51; GH54; GH62; GH127; GH137; GH142; GH146</td>
					</tr>
					<tr>
						<td style=min-width:50px>Xyloglucan-specific endo-β-1,4-glucanase</td>
						<td style=min-width:50px>GH5; GH9; GH12; GH16; GH26; GH44; GH74</td>
					</tr>
					<tr>
						<td style=min-width:50px>Glucuronoarabinoxylan-specific endo-β-1,4-xylanase</td>
						<td style=min-width:50px>GH30</td>
					</tr>
					<tr>
						<td style=min-width:50px>Arabinoxylan-specific endo-β-1,4-xylanase</td>
						<td style=min-width:50px>GH5</td>
					</tr>
					<tr>
						<td style=min-width:50px>Acetyl xylan esterase</td>
						<td style=min-width:50px>CE1; CE2; CE3; CE4; CE5; CE6; CE7; CE12; CE15</td>
					</tr>
					<tr>
						<td style=min-width:50px>LPMO</td>
						<td style=min-width:50px>AA9; AA14</td>
					</tr>
					<tr>
						<td style=min-width:50px>Xylan Binding Modules</td>
						<td style=min-width:50px>CBM2; CBM4; CBM6; CBM9; CBM13; CBM15; CBM22; CBM31; CBM35; CBM36; CBM37; CBM42; CBM54; CBM59; CBM60; CBM72</td>
					</tr>
					<tr>
						<td style=min-width:50px>Mannan Binding Modules</td>
						<td style=min-width:50px>CBM13; CBM16; CBM23; CBM27; CBM29; CBM35; CBM59; CBM62; CBM72; CBM76; CBM80</td>
					</tr>
					<tr>
						<td style=min-width:50px>Arabinoxylan binding modules</td>
						<td style=min-width:50px>CBM13; CBM42; CBM62</td>
					</tr>
					<tr>
						<td style=min-width:50px>Xyloglucan Binding Modules</td>
						<td style=min-width:50px>CBM44; CBM62; CBM65; CBM75; CBM76; CBM78; CBM80; CBM81</td>
					</tr>
				</table>
				</div>
	  </div>
	  <div class="plant-cells" id="Lignin">
			<h1><b><u>Lignin</h1></b></u>
			<div class="table-responsive">    
				<table class="table table-striped">
				
					<tr>
						<td style=min-width:50px><b><u>CAZy Class</b></u></td>
						<td style=min-width:50px><b><u>CAZymes</b></u></td>
					</tr>
					<tr>
						<td style=min-width:50px>AA1</td>
						<td style=min-width:50px>Laccase; p-diphenol oxygen oxidoreductase; Ferroxidase; Laccase-like multicopper oxidase</td>
					</tr>
					<tr>
						<td style=min-width:50px>AA2</td>
						<td style=min-width:50px>Lignin peroxidase; Manganese peroxidase; Versatile peroxidase; Peroxidase</td>
					</tr>
					<tr>
						<td style=min-width:50px>AA3</td>
						<td style=min-width:50px>Aryl-alcohol oxidase; Alcohol oxidase; Pyranose Oxidase; Cellobiose dehydrogenase; GMC-Oxidoreductases</td>
					</tr>
					<tr>
						<td style=min-width:50px>AA4</td>
						<td style=min-width:50px>Vanillyl alcohol oxidase</td>
					</tr>
					<tr>
						<td style=min-width:50px>AA5</td>
						<td style=min-width:50px>Alcohol oxidase; Glyoxal oxidase; Galactose Oxidase</td>
					</tr>
					<tr>
						<td style=min-width:50px>AA6</td>
						<td style=min-width:50px>1,4-benzoquinone reductase</td>
					</tr>
					<tr>
						<td style=min-width:50px>AA8</td>
						<td style=min-width:50px>Iron reductase</td>
					</tr>
					<tr>
						<td style=min-width:50px>LPMO</td>
						<td style=min-width:50px>AA9; AA10; AA11; AA13; AA14; AA15</td>
					</tr>
					<tr>
						<td style=min-width:50px>AA12</td>
						<td style=min-width:50px>Pyrroloquinoline quinone-dependent oxidoreductase</td>
					</tr>
					<tr>
						<td style=min-width:50px>CE1</td>
						<td style=min-width:50px>Feruloyl esterase; Cinnamoyl esterase</td>
					</tr>
					<tr>
						<td style=min-width:50px>CE15</td>
						<td style=min-width:50px>4-O-methyl-glucuronoyl methylesterase</td>
					</tr>
					<tr>
						<td style=min-width:50px>CE10</td>
						<td style=min-width:50px>Aryl esterase; Carboxyl esterase</td>
					</tr>
				</table>
				</div>
	  </div>
	  <div class="plant-cells" id="Pectin">
			<h1><b><u>Pectin</h1></b></u>
			<div class="table-responsive">    
				<table class="table table-striped">
					<tr>
						<td style=min-width:50px><b><u>CAZymes</b></u></td>
						<td style=min-width:50px><b><u>CAZy Class</b></u></td>
					</tr>
					<tr>
						<td style=min-width:50px>Polygalacturonase; exo-polygalacturonase; exo-poly-galacturonosidase; rhamnogalacturonase; rhamnogalacturonan α-1,2-galacturonohydrolase</td>
						<td style=min-width:50px>GH28</td>
					</tr>
					<tr>
						<td style=min-width:50px>α-L-rhamnosidase</td>
						<td style=min-width:50px>GH28; GH33; GH78; GH106</td>
					</tr>
					<tr>
						<td style=min-width:50px>exo-polygalacturonase</td>
						<td style=min-width:50px>GH4</td>
					</tr>
					<tr>
						<td style=min-width:50px>Rhamnogalacturonan α-L-rhamnohydrolase</td>
						<td style=min-width:50px>GH78; GH106</td>
					</tr>
					<tr>
						<td style=min-width:50px>α-L-arabinofuranosidase</td>
						<td style=min-width:50px>GH2; GH3; GH10; GH43; GH51; GH54; GH62</td>
					</tr>
					<tr>
						<td style=min-width:50px>exo-α-L-1,5-arabinanase</td>
						<td style=min-width:50px>GH93</td>
					</tr>
					<tr>
						<td style=min-width:50px>β-galactosidase</td>
						<td style=min-width:50px>GH1; GH2; GH3; GH35; GH39; GH42; GH50; GH59; GH147</td>
					</tr>
					<tr>
						<td style=min-width:50px>Pectate lyase</td>
						<td style=min-width:50px>PL1; PL2; PL3; PL9; PL10</td>
					</tr>
					<tr>
						<td style=min-width:50px>exo-pectate lyase</td>
						<td style=min-width:50px>PL1; PL2; PL9</td>
					</tr>
					<tr>
						<td style=min-width:50px>Pectin Lyase</td>
						<td style=min-width:50px>PL1</td>
					</tr>
					<tr>
						<td style=min-width:50px>Rhamnogalacturonan endolyase</td>
						<td style=min-width:50px>PL4; PL9; PL11</td>
					</tr>
					<tr>
						<td style=min-width:50px>Rhamnogalacturonan exolyase</td>
						<td style=min-width:50px>PL11; PL26</td>
					</tr>
					<tr>
						<td style=min-width:50px>Oligogalacturonate lyase</td>
						<td style=min-width:50px>PL22</td>
					</tr>
					<tr>
						<td style=min-width:50px>Pectin methylesterase</td>
						<td style=min-width:50px>CE8</td>
					</tr>
					<tr>
						<td style=min-width:50px>Pectin acetylesterase; Rhamnogalacturonan acetylesterase</td>
						<td style=min-width:50px>CE12</td>
					</tr>
					<tr>
						<td style=min-width:50px>Pectin acetylesterase</td>
						<td style=min-width:50px>CE13</td>
					</tr>
					<tr>
						<td style=min-width:50px>Acetylesterase</td>
						<td style=min-width:50px>CE6</td>
					</tr>
					<tr>
						<td style=min-width:50px>Pectin Binding Modules</td>
						<td style=min-width:50px>CBM41; CBM77</td>
					</tr>
					<tr>
						<td style=min-width:50px>Galactan binding Modules</td>
						<td style=min-width:50px>CBM32; CBM35; CBM61; CBM62; CBM80</td>
					</tr>
					<tr>
						<td style=min-width:50px>L-Rhamnose Binding Modules</td>
						<td style=min-width:50px>CBM67</td>
					</tr>
					<tr>
						<td style=min-width:50px>Arabinogalactan Binding Modules</td>
						<td style=min-width:50px>CBM62</td>
					</tr>
				</table>
				</div>
	  </div>
	  <div class="plant-cells" id="Starch">
			<h1><b><u>Starch</h1></b></u>
			<div class="table-responsive">    
				<table class="table table-striped">
					<tr>
						<td style=min-width:50px><b><u>CAZymes</b></u></td>
						<td style=min-width:50px><b><u>CAZy_class</b></u></td>
					</tr>
					<tr>
						<td style=min-width:50px>α-amylase</td>
						<td style=min-width:50px>GH13; GH14; GH57; GH119; GH126</td>
					</tr>
					<tr>
						<td style=min-width:50px>LPMO</td>
						<td style=min-width:50px>AA13</td>
					</tr>
					<tr>
						<td style=min-width:50px>α-glucosidase</td>
						<td style=min-width:50px>GH4; GH31; GH63; GH97; GH122</td>
					</tr>
					<tr>
						<td style=min-width:50px>Starch phosphorylase</td>
						<td style=min-width:50px>GT35</td>
					</tr>
					<tr>
						<td style=min-width:50px>Starch Binding Modules</td>
						<td style=min-width:50px>CBM20; CBM21; CBM25; CBM26; CBM34; CBM45; CBM53; CBM69; CBM74; CBM82; CBM83</td>
					</tr>
				</table>
				</div>
	  </div>
	  <div class="plant-cells" id="Inulin">
			<h1><b><u>Inulin</h1></b></u>
			<div class="table-responsive">    
				<table class="table table-striped">
				
					<tr>
						<td style=min-width:50px><b><u>CAZymes</b></u></td>
						<td style=min-width:50px><b><u>CAZy Class</b></u></td>
					</tr>
					<tr>
						<td style=min-width:50px>Endo-Inulinase</td>
						<td style=min-width:50px>GH32</td>
					</tr>
					<tr>
						<td style=min-width:50px>Exo-Inulinase</td>
						<td style=min-width:50px>GH32</td>
					</tr>
					<tr>
						<td style=min-width:50px>Inulin lyase</td>
						<td style=min-width:50px>GH91</td>
					</tr>
					<tr>
						<td style=min-width:50px>Inulin Binding Module</td>
						<td style=min-width:50px>CBM38</td>
					</tr>
				</table>
				</div>
	  </div>
    </div>
  </div>
</div>
		<p><b><font color="black"><font size="4"><font face="garamond"><u> References</u></b></font></p>
	    <p><b><font color="blue"><font size="3"><font face="garamond">1. Keegstra, Kenneth. "Plant cell walls." Plant physiology 154, no. 2 (2010): 483-486.</u></b></font></p>
		<p><b><font color="blue"><font size="3"><font face="garamond">2. Höfte, Herman, and Aline Voxeur. "Plant cell walls." Current Biology 27, no. 17 (2017): R865-R870.</u></b></font></p>
		<p><b><font color="blue"><font size="3"><font face="garamond">3. Dey, Prakash M., and Ken Brinson. "Plant cell-walls." In Advances in Carbohydrate Chemistry and Biochemistry, vol. 42, pp. 265-382. Academic Press, 1984.</u></b></font></p>
		<p><b><font color="blue"><font size="3"><font face="garamond">4. Kameshwar, A. K. S., and WenSheng Qin. "Recent developments in using advanced sequencing technologies for the genomic studies of lignin and cellulose degrading microorganisms." International Journal of Biological Sciences 12, no. 2 (2016): 156-171.</u></b></font></p>
		<p><b><font color="blue"><font size="3"><font face="garamond">5. Pérez, J., J. Munoz-Dorado, T. D. L. R. de la Rubia, and J. Martinez. "Biodegradation and biological treatments of cellulose, hemicellulose and lignin: an overview." International microbiology 5, no. 2 (2002): 53-63.</u></b></font></p>
		<p><b><font color="blue"><font size="3"><font face="garamond">6. Saxena, R. C., D. K. Adhikari, and H. B. Goyal. "Biomass-based energy fuel through biochemical routes: a review." Renewable and Sustainable Energy Reviews 13, no. 1 (2009): 167-178.</u></b></font></p>

<script>
	function show_selected_cell(current_id) {
	  console.log(current_id);
	  var c = document.getElementsByClassName("plant-cells");
	  for(i=0;i<c.length;i++)
		c[i].style.display = "none";
	  document.getElementById(current_id).style.display="block";	
}

</script>
</body>
</html>



