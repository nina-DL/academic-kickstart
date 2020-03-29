+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Research Interests"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

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
  #image = "headers/bubbles-wide.jpg"  # Name of image in `static/img/`.
  #image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  #image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  #image_position = "center"  # Options include `left`, `center` (default), or `right`.
  #image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  #text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  #padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

My main research interest lies at the intersection between **Bayesian methods**, **Statistical Reinforcement Learning** & **Multi-armed Bandits**, and modern applications based on adaptive decision making, which include **Dynamic Treatment Regimes (DRTs)**, **mobile-Health (mHealth)**, and other **adaptive experimentations** such as educational trials.  

During my Master’s I focused on Bayesian Statistics, specifically Markov Chain Monte Carlo methods, and Deep Learning Algorithms, both with (spatio-)temporal applications. 

After starting my PhD, I got really interested in Reinforcement Learning (RL) and its statistical properties in terms of inference and causality, particularly relevant in bio-medical settings.
My first approach was to carefully review all the RL algorithm applied in modern biostatistic, identifying, first, all the health-related applications, and then the relative methodologies.

Currently, I'm focusing on problems and challenges arising in some of these specific applications and the related statistical approach evaluation. More specifically, my attention is now on:
- MABs with non-stationarity settings, typical of real-world mHealth problems where habituation is a main challenge;
- Non-stationarity and habituation modeling in complex multi-factorial designs;
- Statistical inference in MABs online adaptive experiments, where the primary interest is generally on maximising an expected cumulative reward;
- Design of adaptive randomized trials.

I have also worked for a couple of years in a clinical foundation, collaborating with clinicians and healthcare researchers. I think that statistics and machine learning (ML) can bring a lot in advancing the health-related research and, reversely, that many of the interesting challenges and problems in statistics and ML araise from real-worls applications.

{{% alert note %}}
Here are nice readings to get into RL, MABs, DTRs and mhealth:
- [Algorithms for Reinforcement Learning](chrome-extension://oemmndcbldboiebfnladdacbdfmadadm/https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf) by Csaba Szepesvari
- [Bandit Algorithms](chrome-extension://oemmndcbldboiebfnladdacbdfmadadm/https://tor-lattimore.com/downloads/book/book.pdf) by Tor Lattimore and Csaba Szepesvari
- [Statistical Methods for Dynamic Treatment Regimes](https://link.springer.com/book/10.1007/978-1-4614-7428-9) by Bibhas Chakraborty and Erica E.M. Moodie
- [Mobile Health: Sensors, Analytic Methods, and Applications](https://www.springer.com/gp/book/9783319513935) by James M. Rehg, Susan A. Murphy, Santosh Kumar (Eds.)
{{% /alert %}}
