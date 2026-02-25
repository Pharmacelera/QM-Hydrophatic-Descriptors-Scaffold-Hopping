Material related to the paper entitled: “Assessment of Quantum Mechanics-Based Hydrophatic Descriptors to Navigate the Isofunctional Chemical Space in Scaffold Hopping”


PART1. Validation of isofunctional molecules

The original 'Large-Hops' (LH) benchmark dataset reported by Pinel et al. (Mol. Inform. 42(4): e202200216) is accessible from: https://github.com/iktos/scaffold-hopping  

Folder: “LH_subset”
Content: The dataset includes a list of subfolders corresponding to each of the 12 systems from the LH subset selected for this study, along with the associated rankings (.csv format) derived from ligand-based screening with 3D HyPhar descriptors. 
•	“SH_S1_ID_1c5q_1gi4” (gene name: TRP1)
•	“SH_S47_ID_4b70_4zsp” (gene name: BACE1)
•	“SH_S17_ID_2oqv_3hab” (gene name: DPP4)
•	“SH_S90_ID_5diq_5djp” (gene name: FPPS)
•	“SH_S77_ID_2v5a_2w71” (gene name: accC)
•	“SH_S58_ID_4mvx_4zt5” (gene name: MetRS)
•	“SH_S4_ID_3prz_3qar” (gene name: PIK3CG)
•	“SH_S96_ID_3l3l_5xsu” (gene name: PARP1)
•	“SH_S34_ID_5vp0_5xkm” (gene name: PDE2A)
•	“SH_S86_ID_6hu2_6hu3” (gene name: HDAC8)
•	“SH_S102_ID_2y71_4b6o” (gene name: aroQ)
•	“SH_S24_ID_4oho_4op1” (gene name: GCKR)

For each subfolder:
•	ranking_{ID}_{SIM}.csv: rankings based on template ID (“ref0” and “ref1”) and Tanimoto, Tversky and Carbó (SIM) similarity metrics.
•	{gene_name}_refs.sdf: 3D overlays for each template (“ref_0” and “ref_1”).


PART2. Validation of isofunctional fragments

Relevant input/output data related to BACE1, DPP4 and PARP1 systems considered for the exploration of the isofunctional fragments.

Folder: “BACE1”
Content:
•	BACE1_3D-overlays_actives.pse: 3D overlays of the 39 active fragment for BACE1 from alignment-based (AB) and docking-based (DB) protocols. 3D structure of BACE1 (PDB code: 4frj) and templates SC_ref0 and SC_ref1.
•	BACE1_decoys.smi: smiles codes for the 5,000 decoys extracted from DUD-E for BACE1.
•	BACE1-glide-grid_4frj-glide-grid.zip: grid file used for docking with Glide.
•	BACE1_AB.csv: output similarity scores by reference (SC_ref0, SC_ref1) for the 39 actives + 5,000 decoys obtained from rescoring with Tanimoto, Tversky and Carbó metrics for alignment-based (AB) protocol. Canonical smiles are also included.
•	BACE1_DB.csv: output similarity scores by reference (SC_ref0, SC_ref1) for the 39 actives + 4,202 decoys obtained from rescoring with Tanimoto, Tversky and Carbó metrics for docking-based (DB) protocol and docking scores (kcal/mol). Canonical smiles are also included.

Folder: “DPP4”
Content:
•	DPP4_3D-overlays_actives.pse: 3D overlays of the 47 active fragment for DPP4 from alignment-based (AB) and docking-based (DB) protocols. 3D structure of DPP4 (PDB code: 2oqv) and templates SC_ref0 and SC_ref1.
•	DPP4_decoys.smi: smiles codes for the 5,000 decoys extracted from DUD-E for DPP4.
•	DPP4_glide-grid_2oqv-glide-grid.zip: grid file used for docking with Glide.
•	DPP4_AB.csv: output similarity scores by reference (SC_ref0, SC_ref1) for the 47 actives + 5,000 decoys obtained from rescoring with Tanimoto, Tversky and Carbó metrics for alignment-based (AB) protocol. Canonical smiles are also included.
•	DPP4_DB.csv: output similarity scores by reference (SC_ref0, SC_ref1) for the 47 actives + 3,629 decoys obtained from rescoring with Tanimoto, Tversky and Carbó metrics for docking-based (DB) protocol and docking scores (kcal/mol). Canonical smiles are also included.

Folder: “PARP1”
Content:
•	PARP1_3D-overlays_actives.pse: 3D overlays of the 77 active fragment for PARP1 from alignment-based (AB) and docking-based (DB) protocols. 3D structure of PARP1 (PDB code: 4pjt) and templates SC_ref0 and SC_ref1.
•	PARP1_decoys.smi: smiles codes for the 5,000 decoys extracted from DUD-E for PARP1.
•	PARP1_glide-grid_4pjt-glide-grid.zip: grid file used for docking with Glide.
•	PARP1_AB.csv: output similarity scores by reference (SC_ref0, SC_ref1) for the 77 actives + 5,000 decoys obtained from rescoring with Tanimoto, Tversky and Carbó metrics for alignment-based (AB) protocol. Canonical smiles are also included.
•	PARP1_DB.csv: output similarity scores by reference (SC_ref0, SC_ref1) for the 77 actives + 1,517 decoys obtained from rescoring with Tanimoto, Tversky and Carbó metrics for docking-based (DB) protocol and docking scores (kcal/mol). Canonical smiles are also included.
