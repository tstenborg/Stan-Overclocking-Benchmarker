# Stan-Overclocking-Benchmarker

Benchmarking Stan under Dynamic Overclocking with ThrottleStop.

---

<figure style="width:509px;">
  <img src="RuntimeExamples.png" alt="Example runtimes for Stan's Bayesian inference with and without system overclocking." width="509" height="489">
  <figcaption>Figure 1. Example runtimes for Stan's Bayesian inference with and without system overclocking. Inference of type Ia supernovae cosmological parameters was used as an example problem. Runtime variance was lower under overclocking. Hyperthreading was counterproductive. Execution configurations, moderated by ThrottleStop, were...<br /><br />

&nbsp;&nbsp; Top (left) overclocking, physical cores, (right) no overclocking, physical cores.<br />
&nbsp;&nbsp; Bottom (left) overclocking, logical cores, (right) no overclocking, logical cores.

Adapted from Stenborg (2025), below.</figcaption>
</figure>

---

### Key Files

- StanOverclockingBenchmarker.Rmd &nbsp;&nbsp; R markdown. Incorporates Stan's R interface, RStan.<br />

### Software Requirements

- R.<br />
- R IDE, e.g., RStudio.<br />

### Reference

Stenborg, TN 2025, "[Benchmarking Stan under Dynamic Overclocking with ThrottleStop](https://www.aspbooks.org/publications/538/265.pdf)", in S Gaudet, D Bohlender, S Gwyn, A Hincks, and P Teuben (eds), Astronomical Data Analysis Software and Systems XXXII, Astronomical Society of the Pacific Conference Series, vol 538, pp. 265&ndash;268.
