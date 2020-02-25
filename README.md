## Overview

Welcome to the Interactive Safety Graphics home page. We make open source interactive graphics for monitoring clinical trial safety. Check out a [sample graphic](https://safetygraphics.github.io/hep-explorer/test-page/example1) along with its paired [clinical workflow](https://github.com/SafetyGraphics/SafetyGraphics.github.io/raw/master/guide/HepExplorerWorkflow_v1_2.pdf) based on the medical literature, or explorer your own data using the [safetyGraphics R package](#safetygraphics-r-package) shown below.

![edishapp-take2_smallish](https://user-images.githubusercontent.com/3680095/51296057-e3195380-19df-11e9-971a-430c3be930a4.gif)

## Background

The Interactive Safety Graphics (ISG) subteam of the ASA Biopharm-DIA Safety Working Group is an interdisciplinary effort that, amongst other things, seeks to provide a clinical safety workflow for monitoring during clinical development in an open source model. Click [here](about) to learn more about our team's motivation, see a full list of team members. You can also explore our [road map](roadmap) to learn more about our active and planned projects.

## safetyGraphics R Package

The safetyGraphics R package makes it easy for users to evaluate thier own clinical trial safety data in R. The package provides a simple workflow to load lab data from clinical trials (AdAM or SDTM preferred).

To learn more you can:

- See the package on [CRAN](https://cran.r-project.org/web/packages/safetyGraphics/index.html)
- Download the [clinical workflow](https://github.com/SafetyGraphics/SafetyGraphics.github.io/raw/master/guide/HepExplorerWorkflow_v1_2.pdf)
- View the [vignette](https://cran.r-project.org/web/packages/safetyGraphics/vignettes/shinyUserGuide.html) for detailed guidance on using the Shiny application
- Explore the [github repo](https://github.com/SafetyGraphics/safetyGraphics) for the package
- Check out the underlying [javascript library](https://github.com/SafetyGraphics/hep-explorer) used to create the [Hepatic Safety Explorer Chart](https://safetygraphics.github.io/hep-explorer/test-page/example1)
- See [the poster](https://github.com/RhoInc/RStudioConf2019-ePoster/) we presented at RStudio::conf(2019)
- Try out a hosted version of the [shiny app](https://becca-krouse.shinyapps.io/safetyGraphicsApp/) (or run it locally using the code in the capsule summary above)
- Check out [other interactive graphics](https://rhoinc.github.io/safety-explorer-suite/) for safety monitoring.  We also wrote [a paper](https://journals.sagepub.com/doi/abs/10.1177/2168479018754846) about these. Our plan is to add some of them to SafetyGraphics package in future releases.
- Take a look at the [technical framework](https://user-images.githubusercontent.com/3680095/51296179-6f2b7b00-19e0-11e9-841a-afc2964a7e1a.png) being used to create the chart
