Download
===========================

Gzipped BED (bed.gz) and TABIX (bed.gz.tbi) files can be downloaded here:
TAGOOS files

.. list-table:: TAGOOS BED and TBI files
   :widths: 15 10 30
   :header-rows: 1

   * - Size
     - Last modified
     - File name
   * - 1.2G
     - May -26-2018
     - `tagoos_intergenic_hg19.bed.gz <http://pedagogix-tagc.univ-mrs.fr/~gonzalez/tagoos/release/180328/tagoos_intergenic_hg19.bed.gz>`_
   * - 685K
     - May -26-2018
     - `tagoos_intergenic_hg19.bed.gz.tbi <http://pedagogix-tagc.univ-mrs.fr/~gonzalez/tagoos/release/180328/tagoos_intergenic_hg19.bed.gz.tbi>`_
   * - 1.2G
     - May -26-2018
     - `tagoos_intergenic_hg38.bed.gz <http://pedagogix-tagc.univ-mrs.fr/~gonzalez/tagoos/release/180328/tagoos_intergenic_hg38.bed.gz>`_
   * - 684K
     - May -26-2018
     - `tagoos_intergenic_hg38.bed.gz.tbi <http://pedagogix-tagc.univ-mrs.fr/~gonzalez/tagoos/release/180328/tagoos_intergenic_hg38.bed.gz.tbi>`_
   * - 2.0G
     - May -26-2018
     - `tagoos_intronic_hg19.bed.gz <http://pedagogix-tagc.univ-mrs.fr/~gonzalez/tagoos/release/180328/tagoos_intronic_hg19.bed.gz>`_
   * - 754K
     - May -26-2018
     - `tagoos_intronic_hg19.bed.gz.tbi <http://pedagogix-tagc.univ-mrs.fr/~gonzalez/tagoos/release/180328/tagoos_intronic_hg19.bed.gz.tbi>`_
   * - 2.0G
     - May -26-2018
     - `tagoos_intronic_hg38.bed.gz <http://pedagogix-tagc.univ-mrs.fr/~gonzalez/tagoos/release/180328/tagoos_intronic_hg38.bed.gz>`_
   * - 754K
     - May -26-2018
     - `tagoos_intronic_hg38.bed.gz.tbi <http://pedagogix-tagc.univ-mrs.fr/~gonzalez/tagoos/release/180328/tagoos_intronic_hg38.bed.gz.tbi>`_


Column descriptions of bed files

1. Chromosome number with "chr" suffix. It goes from 1 to 22, i.e. no X o Y chromosomes.
2. Starting position (zero-based).
3. End position (one-based).
4. Comma-separated list of annotation variables.
5. Score.
6. p-value. 

**File line example**

Example line for the rs227727 SNP (chr17:54776954-54776955 in hg19 genome)

.. code-block:: bash

    chr17	54776954	54776955	dnaseseq.bodyofpancreasmaleadult_54years_.encode2,dnaseseq.brainmalefetal_72days_andmalefetal_76days_.encode2,dnaseseq.dedifferentiatedamnioticfluidmesenchymalstemcell.encode2,dnaseseq.gastrocnemiusmedialismaleadult_54years_.encode2,dnaseseq.h7hesc.encode2,dnaseseq.lungfemalefetal_85days_.encode2,dnaseseq.muscleoftrunkfemalefetal_113days_.encode2,dnaseseq.placentamalefetal_85days_.encode2,eqtl.Esophagus_Muscularis.gtex,faireseq.htr8_svneo.encode2,h2afz.inducedpluripotentstemcellmaleadult_53years_originatedfromfibroblastofarm.encode2,h2az.brst_hmec.roadmap,h3f3a.neuralprogenitorcelloriginatedfromh9.encode2,h3k27ac.BI_Skeletal_Muscle.youngh3k27ac,h3k27ac.Fetal_muscle.youngh3k27ac,h3k27ac.HCC1954.youngh3k27ac,h3k27ac.HCT-116.youngh3k27ac,h3k27ac.HSMMtube.youngh3k27ac,h3k27ac.HUVEC.youngh3k27ac,h3k27ac.HeLa.youngh3k27ac,h3k27ac.UCSD_Esophagus.youngh3k27ac,h3k27ac.UCSD_Lung.youngh3k27ac,h3k27ac.esdr_cd184_endo.roadmap,h3k27ac.fat_adip_nuc.roadmap,h3k27ac.gi_rect_sm_mus.roadmap,h3k27ac.lng.roadmap,h3k27ac.rwpe2.encode2,h3k27ac.sknsh.encode2,h3k27ac.strm_chon_mrw_dr_msc.roadmap,h3k27ac.u87.youngh3k27ac,h3k27me3.skin_pen_frsk_mel_03.roadmap,h3k27me3.sknshtreatedwithalltransretinoicacid.encode2,h3k4me1.esophagusmuscularismucosafemaleadult_53years_.encode2,h3k4me1.mus_trnk_fet.roadmap,h3k4me1.spinalcordfemalefetal_108days_.encode2,h3k9me3.cd4positivehelpertcellmaleadult_37years_.encode2	0.276	0.0033545109659




