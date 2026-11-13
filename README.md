### Guillermo Bravo Morante, PhD

Scientific software developer in Vienna, working on **3D imaging, medical CT and shape analysis**.
I trained as a biological and forensic anthropologist, and I now build the tools I used to need:
CT segmentation, automated 3D landmarking, and tested, transparent geometric morphometrics.

**What I'm working on**

- An automated 3D landmarking pipeline that goes from CT and surface scans to analysis-ready
  landmarks: bone segmentation, multi-template deformable registration on the GPU, and an
  uncertainty-ranked review queue. In an early leave-one-out benchmark (13 specimens, 156 registrations),
  mean landmark error fell from 11.38 mm with one deformable template to 5.86 mm with 12-template consensus.
  The full desktop workflow and study data are private.
- A desktop application for geometric morphometrics, for research and teaching. Its
  numerical core is public as [`gmm-core`](https://github.com/gbravomorante/gmm-core).

**Open source**

| Project | What it is |
| --- | --- |
| [**gmm-core**](https://github.com/gbravomorante/gmm-core) | Geometric morphometrics in Python: importers for several common landmark formats, Procrustes analysis, quality control and RRPP-based shape statistics. About 300 tests. |
| [**torch-cpd**](https://github.com/gbravomorante/torch-cpd) | Non-rigid Coherent Point Drift in PyTorch, checked against pycpd. In a 3,000-point benchmark, the deformable step took 118.7 s with pycpd and about 2 s on an RTX 4080 SUPER. |
| [**fossil-forge**](https://github.com/gbravomorante/fossil-forge) | A local web workbench that turns an open fossil surface scan into a printable, checked solid while preserving the core measured surface. |

**Background**

PhD in physical and forensic anthropology (Granada, with Vienna): 3D geometric morphometrics
for age estimation. Along the way: comparative morphology from CT data, ancient-DNA laboratory
work, and research support at the University of Zurich. I co-authored papers in *Nature*, *Science* and
*Nature Communications*, and led first-author methods work in forensic age estimation.

**Tools**: Python, PyTorch/CUDA, NumPy/SciPy, scikit-learn, R, Open3D, trimesh, MeshLab, 3D Slicer,
TotalSegmentator, three.js · CT segmentation, surface registration, structured-light scanning
(Artec), statistical shape analysis.

[gbravomorante.dev](https://gbravomorante.dev) ·
[ORCID](https://orcid.org/0000-0002-1544-9279) ·
[Google Scholar](https://scholar.google.com/citations?user=NBTWCfoAAAAJ) ·
[LinkedIn](https://www.linkedin.com/in/guillermobravomorante/)
