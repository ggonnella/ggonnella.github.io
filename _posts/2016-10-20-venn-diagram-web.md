---
layout: post
title: A web server for generating Venn and Euler diagrams
---

Who did never use a Venn or Euler Diagram? They present information in a very compact and informative way.
In the past, when I needed to prepare a Venn Diagram for a publication, I worked with the R package [VennDiagram],
developed by the group of Paul C. Boutros.

A new [BMC Bioinformatics paper][lam2016] by Felix Lam and colleagues from the Boutros group presents
the [web server][VennDiagramWeb] where an application allows to create diagrams using
the VennDiagram library.

In general, I am not a big fan of web interfaces: in most cases it is better to
apply analyses in an automated fashion and on multiple samples in batch and
to rely as much as possible on local resources (data and programs) which one
can control.
However, their work is interesting and can be useful.

First, if one wants a quick
diagram, he can just fire up the browser and enter the data. Second, one can then
also extract the R code and save it in a script, so that the diagram remains
reproducible... so one can also use this as a way to automatically generate the
code in an interactive fashion.
Interesting is for sure also the [Shiny] interface
on which their server is based upon.

[lam2016]: https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-1281-5
[VennDiagram]: https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-35
[VennDiagramWeb]: http://venndiagram.res.oicr.on.ca/).
[Shiny]: https://www.rstudio.com/products/shinyapps/
