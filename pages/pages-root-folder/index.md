---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_yc.jpg
teaser: "The Chen Lab at Peking University combines bioengineering, molecular biology, cell biology, fluorescence imaging, and nanotechnology to create novel nucleic acid-based methods for the detection and/or treatment of human diseases such as cancer and infectious diseases. Specific research interests include nucleic acid nanotechnology, single-molecule imaging, biomolecular engineering, and virus-like particle-based RNA delivery/vaccine technologies. Research in the Chen lab is currently supported by the National Key R&D Program of China and the National Natural Science Foundation of China.<br/><br/><strong>Interested in joining the lab?</strong><br/><br/><strong>We have opportunities for postdoctoral researchers, PhD students, and undergraduate students.</strong><br/><br/>For inquiries email: chenak@pku.edu.cn"
widget1:
  title: "CRISPR/dCas9-based genomic labeling"
  url: '/publication/WXT-CRISPR-MB/'
  image: WXT-NAR.jpg
  text: 'We have developed a novel live-cell genomic imaging platform, termed CRISPR/MB, which comprises dCas9, an MB, and an sgRNA engineered with an MB target sequence in the stem–loop 2 region, and demonstrated its capacity for quantitative, dynamic and dual-color analysis of genomic loci in human cells.'
widget2:
  title: "RNA nanostructure-based therapeutics"
  url: '/publication/QN-RNA-self-assemble-structure/'
  image: QN-TB-Gag-thumb.jpg
  text: 'We have developed self-assembled RNA nanostructures that can inhibit HIV-1 virus assembly, achieved through hybridization of multiple artificial small RNAs with a stem–loop structure (STL) that we identify as a prominent ligand of Gag that can inhibit virus particle production via STL-Gag interactions.'
widget3:
  title: "Demystifying retroviral assembly"
  url: '/publication/YYT-Gag-RNA/'
  image: YYT-PNAS.jpg
  text: 'In contrast to the general notion that vRNA only triggers Gag assembly and is dispensable for subsequent assembly, we found that vRNA is indispensable throughout assembly, scaffolding the formation of assembly intermediates and maintaining their architectures via balancing of external forces acting on the assembly environment.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
# callforaction:
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features ›
#   style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
