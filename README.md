# Gamma-ray burst photon analysis

COSMOS UC Irvine 2025, Cluster 4 — Dylan Zhang, Hemanth Pabbaraju, Melissa Hong, Nick Schültz, and Ryan Liu (poster author list).

These notebooks visualize photon arrival times and energies from gamma-ray bursts. The project examined possible energy-dependent arrival-time differences using four bursts from Fermi data; the poster discusses implications for proposed quantum-gravity effects.

## Research question
Do the selected gamma-ray bursts show timing patterns consistent with the proposed energy-dependent photon velocity model?

## Structure
- `notebooks/`: two distinct existing light-curve notebooks, including an energy-split comparison.
- `data/`: four small supplied photon time/energy text files.
- `figures/`: retained notebook plots.
- `docs/`: provenance, validation and limitations.

## Setup and run
Notebook metadata records Python **3.11.9**.
```sh
python -m pip install -r requirements.txt
python -m jupyterlab notebooks
```
Open either notebook and run from its notebook directory. Data paths were made relative and `%matplotlib notebook` was changed to `%matplotlib inline` for portability; scientific calculations and saved outputs were retained.

## Data sources
The poster identifies the Fermi Gamma-ray Space Telescope. The provided files are `photon_time_energy_GRB080916C.txt`, `photon_time_energy_GRB090510.txt`, `photon_time_energy_GRB090926.txt`, and `photon_time_energy_GRB130427A.txt`. They also occur in the user's downloaded `cosmos2017-master.zip` teaching-material archive. They contain energy and arrival-time columns read directly by NumPy. [TODO: add the original archive URL, Fermi query selections, and redistribution license.] No additional download is needed for these small supplied files.

## Poster and acknowledgments
[Poster](https://docs.google.com/presentation/d/1mHrmd4pniw4-L22sALgCPd0VCJbFgD96s0M89SetcsI/edit) · [Group materials](https://drive.google.com/drive/folders/1_uYZ7oOUZjtXTDYtwLWRNd1uVEz0uviV)

Acknowledgments from the poster include Dr. Manoj Kaplinghat, Jay Krishnan, Jake Rudolph, Tyler Smith, Christian Quinteros, UC Irvine and COSMOS. Some other acknowledgment names in the poster are blank and are not invented here. [TODO: specify Dylan's personal contribution versus group work.]

## Interpretation limits
The poster's broad language about disproving loop quantum gravity exceeds what is established by these plotting notebooks. Treat the outcome as the group's reported interpretation of four bursts, not a general exclusion of the theory. [TODO: verify the model assumptions, time-delay calculation, uncertainty and numerical bounds.] The tutorial archive and unrelated teaching exercises are not uploaded wholesale.
