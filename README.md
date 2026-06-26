## Spatial Templates

This repository contains spatial templates for modeling the gamma-ray emission of Centaurus A (Cen A). The templates are provided in FITS format and were generated from radio observations available through the the [NASA SkyView service](https://skyview.gsfc.nasa.gov/current/cgi/query.pl), following the Fermi-LAT [tutorial](https://fermi.gsfc.nasa.gov/ssc/data/analysis/scitools/extended/extended.html) for extended source analyses.

Two sets of radio templates are provided:
* **WMAP 22 GHz**, this template corresponds to the morphology adopted in the Fermi-LAT 4FGL catalog.
* **Parkes 408 MHz**, compared to the WMAP template, the 408 MHz emission extends over a larger region, providing an alternative description of the giant gamma-ray lobes.


### Available Templates

* **WMAP 22 GHz model**

  * `CenA_WMAP_Global.fits` – Global lobes template.
  * `CenA_WMAP_North.fits` – Northern lobe template.
  * `CenA_WMAP_South.fits` – Southern lobe template.

* **Parkes 408 MHz model**

  * `CenA_Parkes_Global.fits` – Global lobes template.
  * `CenA_Parkes_North.fits` – Northern lobe template.
  * `CenA_Parkes_South.fits` – Southern lobe template.


### Notes

* The **Global** templates include both the northern and southern lobes.
* The **North** and **South** templates isolate the lobes and can be used independently when fitting separate components.
* These templates describe only the extended lobe emission. The Cen A core should be included separately as a point source in the source model.
