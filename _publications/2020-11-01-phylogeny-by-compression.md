---
layout: product

# *****************************************************************************************************************************************************
# user defined... REQUIRED
# *****************************************************************************************************************************************************

title: "Comparing phylogeny by compression to phylogeny by NJp and Bayesian Inference"


# ...............................
# ----> product specific variables
# ...............................

# Team - must match team.title --> links product to team
team: CoBaAB

# Project - must match project.title --> links product to project
# 	- If undefined, categorized as "Past Publication"
project: forest-project

# people for product MUST be supplied --> enables it to appear on corresponding persons 'member' page
people: 
- "John Rogers"
- "DeAngelo Wilson"

# *****************************************************************************************************************************************************
# user defined... OPTIONAL
# *****************************************************************************************************************************************************

# Card description priority: 
#	(1) description variable
#   (2) first 30 chars of "About" (body) section
#   (3) nothing  
description: "A paper submited to the BIBM2020 High Performance Computing on Bioinformatics workshop, regarding the computation of phylogenies using the Normalized Compression Distance."

# if true --> Appears on 'Home' page
featured: true

#NOTE:: images should have the aspect ratio ==> 3 : 2?
# key words MUST all be lowercase (or allows duplicates)
keywords: ["phylogenetics", "computational phylogenetics"]

# Image on Card -- NOTE:: card images should have the aspect ratio ==> 3 : 2?
# 	- IF no "post_image" -> Image in post too
#image: "assets/images/kebab-logo.png"

# Image on post -- above About section -- (Must figure out best dimensions: )
post_image: "assets/images/phylogeny-by-compression-slide.PNG"

# Image in post -- above About section + featured image -- (Must figure out best dimensions: )
#banner_image: "assets/images/computaional_bio_banner.jpg"

# ...............................
# ----> product specific variables
# ...............................

# External link to product 
#product_link: 
# Alternative text linking to product external link
#product_link_text: "Link to paper"

---
We compare the accuracy of the Normalized Compress Distance (NCD) technique for building phylogenetic trees from molecular data with the more widely used techniques of Neighbor joining with _p_-value and Bayesian inference. The NCD algorithm is a distance-based alignment-free method and as such takes unaligned sequence data as input and outputs a distance matrix. The matrix is given as input to FastME, which outputs a tree in Newick format. Every step of this process requires minimal processing and as such provides fast execution times along with minimal restrictions on input data.
