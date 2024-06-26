Sentence Supramodal Areas Atlas (SENSAAS)
================

## Reference

**Labache, L.**, Joliot, M., Saracco, J., Jobard, G., Hesling, I., Zago,
L., … & Tzourio-Mazoyer, N. (2019). A SENtence Supramodal Areas AtlaS
(SENSAAS) based on multiple task-induced activation mapping and graph
analysis of intrinsic connectivity in 144 healthy right-handers. Brain
Structure and Function, 224(2), 859-882. DOI:
[10.1007/s00429-018-1810-2](https://doi.org/10.1007/s00429-018-1810-2)

------------------------------------------------------------------------

## Background

Here we develop and provide an atlas in standardized MNI volume space of
32 sentence-related areas based on a 3-step method. This method combines
the analysis of activation and asymmetry during multiple language tasks
with hierarchical clustering of resting-state connectivity and graph
analyses.

Thirty-two multimodal areas of sentence processing, activated and
leftward asymmetrical during sentence production, reading, and
listening, were identified by comparison with a reference task (word
list production, reading, and listening). The temporal correlations at
rest between these 32 regions enabled the detection of their belonging
to three networks. **Among these networks, one, including 18 regions,
contains the essential language areas (SENT_CORE network)**, *i.e.*,
those whose lesion would cause an alteration in the understanding of
speech.

<p align="center">
<img src="readme_files/sentCore_volume.gif" width="50%" height="50%" />
</p>

------------------------------------------------------------------------

## Data release

The `Atlas` folder contains 4 files:

- `read_me_SENSAAS.rtf`: README file containing information about the
  atlas
- `SENSAAS_MNI_ICBM_152_2mm.nii`: NIfTI file containing the 32 brain
  language regions in the MNI space

<p align="center">
<img src="readme_files/SENSAAS.png" width="70%" height="70%" />
</p>

- `SENSAAS_description.csv`: CSV file containing a full description of
  each region. The first column, *Network*, corresponds to which of the
  three networks a region belongs. The second column, *Abbreviation*, is
  the abbreviation of a region. The third column, *Region*, is the full
  anatomical label of a region. Hemisphere refers to the cerebral
  hemisphere to which a region belongs: “left” corresponds to the
  regions in the left hemisphere (as selected in the paper), “right” to
  the regions in the right hemisphere (useful to compute asymmetries).
  *Index* is the index of each region that is used in the NIfTI file.
  The MNI coordinates (columns *Xmm*, *Ymm*, *Zmm*) of each region’s
  centroid are also provided. *Number of Voxels* and *Volume mm³* are
  the number of voxels and the volume (in cubic millimeters) of each
  region for the 2mm version of the atlas.

- `template_ANTs_80tvs_on_MNI.nii.gz`: brain template used to align the
  atlas on, provided in MNI stereotaxic space (MNI ICBM 152, Template
  sampling size of 2x2x2 mm3 voxels; bounding box, x = -90 to 90 mm, y =
  -126 to 91 mm, z = -72 to 109 mm)

The 3 networks are briefly described below. For researchers interested
in language, they should focus on the 18 brain regions belonging to the
network named **SENT_CORE**.

- **SENT_CORE** included 18 essential sentence processing regions.
- **SENT_VISU** aggregated areas acknowledged as involved in visual
  processing.
- **SENT_MEM** aggregated areas belonging to both the posterior regions
  of the DMN involved in episodic memory.

**SENT_CORE** included areas of the antero-posterior language networks,
named in reference to the Broca–Wernicke model in aphasia literature and
reported with consistency in meta-analyses of healthy individuals mapped
during language tasks. The anterior pole corresponded to the regions
named *F3t*, equivalent to Broca area. The posterior pole corresponded
to Wernicke area (*STS3* & *STS4*).

<p align="center">
<img src="readme_files/metaAnalysis.png" width="85%" height="85%" />
</p>

------------------------------------------------------------------------

## Other atlases that might interest you

- Word-List Multimodal Cortical Atlas:
  [WMCA](https://github.com/loiclabache/WMCA_brainAtlas)
- HAnd MOtor Area atlas:
  [HAMOTA](https://github.com/loiclabache/HAMOTA_brainAtlas)
- Atlas of Lateralized visuospatial Attentional Networks:
  [ALANs](https://github.com/loiclabache/ALANs_brainAtlas)
- Atlas of Intrinsic Connectivity of Homotopic Areas:
  [AICHA](https://www.gin.cnrs.fr/en/tools/aicha/)

------------------------------------------------------------------------

## Questions

Please contact me (Loïc Labache) as <loic.labache@yale.edu> and/or
<loic.labache@ensc.fr>
