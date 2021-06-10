# Julia Workshop - HPC.NRW - Summer 21
<!-- 
<a href="https://github.com/crstnbr/JuliaNRWSS21/raw/main/orga/poster/JuliaNRWSS21_poster.pdf"><img align="right" src="https://github.com/crstnbr/JuliaNRWSS21/raw/main/orga/poster/JuliaNRWSS21_poster.png" width=200px></a> -->

An online Julia workshop for the [HPC.NRW Kompetenznetwerk](https://hpc.dh.nrw) which takes place in July 2021 (22nd - 24th).

In case of questions, feel free to [contact me](http://github.com/crstnbr).

## Preparing for the workshop

### Software and workshop materials

What you need (in short):
  * [Julia 1.6](https://julialang.org/downloads/)
  * [Jupyter](https://jupyter.org) + [IJulia.jl](https://github.com/JuliaLang/IJulia.jl)
  * The workshop materials, i.e. this GitHub repository

#### How to get everything
The workshop uses the latest **Julia version 1.6**. Go to [julialang.org](https://julialang.org/downloads/) and install the appropriate binaries for your operating system.

Apart from Julia itself, you will need a [Jupyter](https://jupyter.org) notebook installation and a bunch of Julia packages (dependencies). The simplest way to install everything is to use the [WorkshopWizard](https://crstnbr.github.io/WorkshopWizard.jl/dev/). Just follow the [usage instructions](https://crstnbr.github.io/WorkshopWizard.jl/dev/usage/#Getting-the-latest-workshop-1). Alternatively, you can use the following terminal commands (you need to have `git` and `julia` available):

```bash
git clone https://github.com/crstnbr/JuliaNRWSS21
cd JuliaNRWSS21
julia install.jl
```

If you are facing any issues you can check out [this troubleshooting section](https://crstnbr.github.io/WorkshopWizard.jl/dev/troubleshooting/).

**Note:** I might still change some of the workshop materials before Monday the 21st. To be on the safe side, make sure you update your local instance of the repository on Monday. (You can always delete your local copy and redownload/`git pull`.)

### Julia syntax

To get the most out of the workshop, make yourself familiar with the basic Julia syntax (variables, loops, functions, etc.) in case you haven't used Julia before. Skimming through the [Manual section](https://docs.julialang.org/en/v1/manual/variables/) of the Julia documentaion is certainly a good idea. Alternatively, you can check out [this](https://nbviewer.jupyter.org/url/www.thp.uni-koeln.de/trebst/Lectures/CompPhys-2020/filled_out_template_01_variablen_datenstrukturen.ipynb) and [this](https://nbviewer.jupyter.org/url/www.thp.uni-koeln.de/trebst/Lectures/CompPhys-2020/filled_out_template_02_funktionen_schleifen_verzweigungen.ipynb) jupyter notebook (german video versions [here](https://vimeo.com/showcase/6910448/video/400175206) and [here](https://vimeo.com/showcase/6910448/video/400261725)). There is also a [longer english video introduction](https://www.youtube.com/watch?v=8h8rQyEpiZA) available.

## Tentative schedule

<a href="https://github.com/crstnbr/JuliaNRWSS21/raw/main/orga/schedule/schedule.pdf"><img src="https://github.com/crstnbr/JuliaNRWSS21/raw/main/orga/schedule/schedule.jpeg" width=720px></a>

## Try it out live! (Beta)

Click on the [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/crstnbr/JuliaNRWSS21-binder/main?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fcrstnbr%252FJuliaNRWSS21%26urlpath%3Dtree%252FJuliaNRWSS21%252F%26branch%3Dmain) badge to dive right into the workshop materials.
