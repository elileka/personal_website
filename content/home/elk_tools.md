+++

headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 80  # Order that this section will appear.

title = "Tools"
subtitle = ""

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

<style>
* {
  box-sizing: border-box;
}

.columnEqL {
  float: left;
  width: 50%;
  padding: 0px;
}

.columnEqR {
  float: right;
  width: 50%;
  padding: 0px;
}

.columnWide {
  float: left;
  width: 60%;
  padding: 5px;
}

.columnNarrow {
  float: left;
  width: 40%;
  padding: 5px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>

<div class="row">
  <div class="columnWide">
    <p><b>MetaEuk</b> is a modular toolkit designed for large-scale gene discovery and annotation in eukaryotic metagenomic contigs. It combines fast and sensitive homology search capabilities with a dynamic programming procedure to recover optimal exons sets. It reduces redundancies in multiple discoveries of the same gene and resolves conflicting gene predictions.
	</p>
  </div>
  <div class="columnNarrow">
	<img src="img\MetaEuk.png" style="height: 250px"/>
	<a href="https://github.com/soedinglab/metaeuk" target="_blank">MetaEuk in GitHub</a>
  </div>
</div>

<br>

<div class="row">
  <div class="columnWide">
    <p><b>TraitRateProp</b> is a method for testing whether the rate of sequence evolution of a protein or genomic region is associated with changes in a binary phenotypic trait. It detects specific sequence sites whose evolutionary rate is most affected following trait transitions, suggesting a shift in functional/structural constraints.
	</p>
  </div>
  <div class="columnNarrow">
	<img src="img\trait_rate_prop_logo.jpg"/>
	<div class="columnEqL">
		&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp<a href="http://traitrate.tau.ac.il/prop/source.php" target="_blank">source</a>
	</div>
	<div class="columnEqR">
		&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp<a href="http://traitrate.tau.ac.il/prop/" target="_blank">webserver</a>
	</div>
  </div>
</div>

<br>

<div class="row">
  <div class="columnWide">
    <p><b>SpartaABC</b> is an Approximate Bayesian Computation (ABC) reject algorithm to infer insertion and deletion (indel) parameters from sequence data. SpartaABC infers the indel-to-substitution rate ratio (IR), the shape parameter (A) of the power law distribution controlling the indel length, and the root length parameter (RL).
	</p>
  </div>
  <div class="columnNarrow">
	<img src="img\SpartaABC_logo.gif" style="height: 250px"/>
	<div class="columnEqL">
		&nbsp&nbsp<a href="http://spartaabc.tau.ac.il/webserver/source.php" target="_blank">source</a>
	</div>
	<div class="columnEqR">
		&nbsp&nbsp<a href="http://spartaabc.tau.ac.il/webserver/" target="_blank">webserver</a>
	</div>
  </div>
</div>

<br>

<div class="row">
  <div class="columnWide">
    <p><b>SimBa-SAl</b> is a simulation-based approach for statistical alignment inference. The SimBa-SAl simulator implements a stochastic evolutionary model of indel formation and generates a long true alignment. It tabulates the probabilities of chop-associated segments (Miklos et al. 2004) based on their frequencies in simulation. The SimBa-SAl inference program takes as input such tabulated chop probabilities and uses them for various statistical alignment computations.
	</p>
  </div>
  <div class="columnNarrow">
	<img src="img\SimBa_SAl_logo.png" style="height: 250px"/>
	<div class="columnEqL">
		&nbsp&nbsp&nbsp<a href="https://github.com/elileka/SimBa_SAl_sim" target="_blank">sim source</a>
	</div>
	<div class="columnEqR">
		&nbsp&nbsp&nbsp<a href="https://github.com/elileka/SimBa_SAl_inf" target="_blank">inf source</a>
	</div>
  </div>
</div>


