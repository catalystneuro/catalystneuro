# CatalystNeuro

Welcome to the CatalystNeuro GitHub org. We make open source software to help neuroscience labs collaborate with each other and access state-of-the-art tools to accelerate their science.

### Core infrastructure
* [NWB Conversion Tools](https://github.com/catalystneuro/nwb-conversion-tools): Python tools for creating NWB files from multiple data sources (under development)
* [HDF5Zarr](https://github.com/catalystneuro/HDF5Zarr): Python tools for reading HDF5 files as using Zarr
* [RoiExtractors](https://github.com/catalystneuro/roiextractors): A common API for reading different optical physiology data formats and converting NWB (under development)
  * [RoiExtractors-GPL](https://github.com/catalystneuro/roiextractors-gpl): An extension to RoiExtractors including imports of GPL licenses

### Lab-specific Neurodata Without Borders (NWB) conversion projects
* [Movshon Lab, NYU](https://github.com/catalystneuro/movshon-lab-to-nwb): Blackrock recordings (under development)
* [Brunton Lab, UW](https://github.com/catalystneuro/brunton-lab-to-nwb): ECoG with natural arm movement (dandiset [#55](https://dandiarchive.org/dandiset/000055/draft))
* [Giocomo Lab, Stanford](https://github.com/catalystneuro/giocomo-lab-to-nwb): SpikeGLX Neuropixel recordings on virtual linear track (dandiset [#53](https://dandiarchive.org/dandiset/000053/draft))
* [Tank Lab, Princeton](https://github.com/catalystneuro/tank-lab-to-nwb): SpikeGLX Neuropixel recordings in a decision making task
  * [ndx-tank-metadata](https://github.com/catalystneuro/ndx-tank-metadata): stores information about the [ViRMEn MATLAB VR program](https://pni.princeton.edu/pni-software-tools/virmen)
* [Allen Institute](https://github.com/catalystneuro/allen-oephys-to-nwb): Simultaneous optical imaging and electrophysiology
* [Buzsaki Lab, NYU](https://github.com/catalystneuro/buzsaki-lab-to-nwb): NeuroScope recordings of various navigation experiments (dandiset [#3](https://dandiarchive.org/dandiset/000003/draft))
* [Groh Lab, Heidelberg](https://github.com/catalystneuro/mease-lab-to-nwb): CED and Syntalos recording systems
* [Buffalo Lab, UW](https://github.com/catalystneuro/buffalo-lab-to-nwb): Blackrock recordings of NHPs in virtual environments
* [Jaeger Lab, Emory](https://github.com/catalystneuro/jaeger-lab-to-nwb): Intan electrophysiology and FRET optical imaging
  * [ndx-FRET](https://github.com/catalystneuro/ndx-fret)

### Customized databases for lab experiment records (based on Alyx)
* [Giocomo Lab, Stanford](https://github.com/catalystneuro/giocomo_db) (under development)
* [Buffalo Lab, UW](https://github.com/catalystneuro/buffalo_db)
