# R Time

## Good resources:
* https://cran.r-project.org/web/views/TimeSeries.html

## R Approaches to Series Interpolation:

### Approaches

### Data structures
* lubridate
* ts -- Time series
* xts -- Extensible time series
* tsibbles
	* Main
		* https://tsibble.tidyverts.org/
	* Conceptual overview
		* https://robjhyndman.com/hyndsight/tsibbles/
	* Inspecting and filling gaps:
		* https://cran.r-project.org/web/packages/tsibble/vignettes/implicit-na.html

## R Approaches to temporal disaggregation

Limitations here might be that many temporal disaggregation approaches assume summary data (rather than instantaneous or sample data) is available for each timestep.

### Packages
* tempdisagg:
	* https://cran.r-project.org/package=tempdisagg
	* Vignette:
		https://cran.r-project.org/web/packages/tempdisagg/vignettes/hf-disagg.html
		
## R Approaches for Time Series Modeling

### Packages

* Forecast (retired)
	* Uses ts data structures
	* https://www.rdocumentation.org/packages/forecast/versions/8.15
	* https://otexts.com/fpp2/
* Fable
	* Uses tsibble data structure / tidyverse approach
	* https://fable.tidyverts.org/
* TimeTK
* modeltime
	* Lots of options here, but this seems like a pretty nice aggregator for different approaches including classical and 
	* https://cran.r-project.org/web/packages/modeltime/index.html
