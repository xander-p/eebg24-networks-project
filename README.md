# Network analysis identified novel disease module in rheumatoid arthritis
This is a repository of the students' project completed during the Eastern European Bioinformatics and Computational Genomics School (July 1-12, 2024, EEBG24). 

**Project contributors:** 
Vitalina Bashynska*, Priman Fau*, Anastasiia Romanenko, Anastasiia Kompaniiets, Polina Havrysh, Matvii Mykhailichenko
(asterisk denotes shared leading contribution)

**Project observers:**
Daria Nishchenko, Nadiia Kasianchuk, Felicia Iordachi

**Project supervisor:** 
Oleksandr Petrenko <oleksandr.petrenko@mutation.me>

**Summary table on the disease module:**

| Gene    | Link to the RA [yes/no] | Source | Mechanism | Is in ClinTrials? (link) |
|---------|-------------------------|--------|-----------|--------------------------|
| AURKA   | yes                     | doi: 10.3389/fimmu.2023.1007624 | AURKA encodes a cell cycle-regulated kinase that appears to play a role in microtubule formation and/or spindle pole stabilization during chromosome segregation. | no |
| BIRC3   | yes                     | [https://doi.org/10.1002/iid3.978](https://doi.org/10.1002/iid3.978) | 1) BIRC2 as an upregulated RA-specific gene 2) BIRC2 acted as a hub gene of the RA-specific protein-protein interaction network | no |
| BTLA    | yes                     | [https://doi.org/10.3389/fimmu.2021.654960](https://doi.org/10.3389/fimmu.2021.654960) | In rheumatoid arthritis (RA) patients, BTLA-expressing CD3+/CD4+/CD8+ T cell proportions are remarkably increased, and the swollen joint count is negatively correlated with the percentage of BTLA+CD8+ T cells | no |
| CCR2    | yes                     | [https://doi.org/10.1016/j.intimp.2023.109755](https://doi.org/10.1016/j.intimp.2023.109755) | CCR2 mRNA expression and the tyrosine phosphorylation levels in CCR2 increased in a rat model of adjuvant-induced arthritis (AIA) | [https://onlinelibrary.wiley.com/doi/epdf/10.1002/art.23591](https://onlinelibrary.wiley.com/doi/epdf/10.1002/art.23591) |
| CD2     | not really              | [https://doi.org/10.1038/ng.479](https://doi.org/10.1038/ng.479) | The CD2 protein is a co-stimulatory molecule on the surface of natural killer cells and T-cells "the strongest evidence of association to RA at rs11586238 on 1p13.1 near the CD2 and CD58 genes" | no |
| CD38    | yes                     | [https://doi.org/10.1159/000516642](https://doi.org/10.1159/000516642), [https://doi.org/10.1186/s13075-018-1578-z](https://doi.org/10.1186/s13075-018-1578-z) | 1) high level of CD38+ NK cells and a low level of CD38+ N-like T cells in RA activate the mTOR pathway in CD4+ T cells among MNCs. This subsequently inhibits the differentiation of CD4+ T cells into Treg cells, enhances Th1/Th2 and Th17/Treg ratios, and ultimately exacerbates RA pathogenesis, including immune imbalance and tolerance disorder; 2) CD38 and plasma cell/plasmablast-related genes are upregulated in ACPA+ RF+ arthralgia and UA disease stages before the onset of RA; (2) CD38 is expressed at the highest level on plasma cells in the peripheral blood compared to other immune cell populations in donors with RA or SLE and healthy donors | [https://doi.org/10.1186/s13075-018-1578-z](https://doi.org/10.1186/s13075-018-1578-z) |
| CD48    | no                      |        | Comment: no great evidence except elevated levels in synovial fluid | no |
| CD69    | yes                     | doi: 10.1002/cti2.1140 | SF CD69+CD103+/-CD8+ memory T cells with TRM features play a role in the pathogenesis of ACPA-positive RA by inducing perforin-mediated citrullinated protein formation. | [https://doi.org/10.2217/imt-2019-0091](https://doi.org/10.2217/imt-2019-0091) |
| CD80    | no                      |        | Comment: no great evidence except elevated levels in synovial fluid | doi:10.1093/rheumatology/kev403 |
| CRTAM   | no                      |        | Comment: a predicted marker of inflammatory processes and a RA biomarker, but no connection to disease development/occurrence | no |
| CTLA4   | yes                     | PMID: 26679631, [https://doi.org/10.1080/1744666X.2019.1579642](https://doi.org/10.1080/1744666X.2019.1579642) | (1) Abatacept is a fusion protein composed of the Fc region of the immunoglobulin G1 (IgG1) fused to the extracellular domain of cytotoxic T lymphocyte-associated antigen (CTLA4). - a therapeutic option (2)Activated B lymphocytes, macrophages, osteoclasts and endothelial cells express the costimulatory molecules (CD80/86) and are downregulated by CTLA-4 blockade. | abatacept ([https://www.tandfonline.com/doi/full/10.1080/1744666X.2019.1579642](https://www.tandfonline.com/doi/full/10.1080/1744666X.2019.1579642)) NCT00048581, NCT00279760 |
| CXCR6   | yes                     | 16200580, DOI:10.1002/art.38816, [https://doi.org/10.3389/fimmu.2022.907733](https://doi.org/10.3389/fimmu.2022.907733) | (1) overexpression of CXCR6 on synovial RA CD4+ T cells (human, mice) (2) CXCR6 and CXCL16 levels are elevated in both RA FLSs and may stimulate FLS proliferation (114). (3) CXCR6 and CXCL16 can promote inflammation by affecting T cell differentiation and homing to joints. | no |
| DEPDC1B | no                      |        |                                               | no |
| GZMA    | yes                     | PMC9977805, 27598995, [https://doi.org/10.1038/s41586-023-06708-y](https://doi.org/10.1038/s41586-023-06708-y) | (1) increased level in plasma (granzyme A) (2) in mice induces osteoclastogenesis in inflammatory arthritis (3) implicated in one type of synovium inflammatome in RA in scRNAseq (Tph = T peripheral helpers) | no |
| GZMK    | yes                     | PMC9977805, [https://www.sciencedirect.com/science/article/pii/S1521694224000019](https://www.sciencedirect.com/science/article/pii/S1521694224000019) (rev), [https://www.nature.com/articles/s41467-024-48620-7](https://www.nature.com/articles/s41467-024-48620-7), [https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2021.726529/full](https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2021.726529/full) | (1) increased level in synovial tissue (granzyme K), (2) perforin, IFNg regulation - expressed by CD8+ cells, (3) CD8 + GZMK+ chromatin state in RA (4) a biomarker in ACPA-negative RA | no |
| HMMR    | no                      |        |                                               | no |
| ICOS    | yes                     | [https://doi.org/10.3389/fimmu.2022.1015831](https://doi.org/10.3389/fimmu.2022.1015831) | This suggests that ICOS contributes to the autoimmune response in RA by facilitating the production of autoantibodies | [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6143914/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6143914/) |
| LAMP3   | no                      |        |                                               | no |
| P2RY10  | yes                     | [https://www.jstage.jst.go.jp/article/pjab/91/8/91_PJA9108B-02/_pdf](https://www.jstage.jst.go.jp/article/pjab/91/8/91_PJA9108B-02/_pdf) | Gwas analysis | no |
| SLAMF1  | yes                     | [https://doi.org/10.3389/fimmu.2022.961129](https://doi.org/10.3389/fimmu.2022.961129) | its involvement in the inflammatory response mediated by infiltrating immune cells in RA | no |
| TIGIT   | yes                     | [https://doi.org/10.3892/etm.2022.11579](https://doi.org/10.3892/etm.2022.11579) | The present study suggests that the increase in TIGIT+PD-1+CXCR5-CD4+T cells is associated with the production of autoantibodies and RA activity and may serve a role in RA pathogenesis. | no |
| UBD     | yes                     | [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9879075/#:~:text=10.3892/mmr.2023.12940](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9879075/#:~:text=10.3892/mmr.2023.12940) | overexpression in RA (array profiling), in cell-based study (RA-fibroblast-like synoviocytes) UBD promoted the secretion of inflammatory factors (IL-2, IL-6, IL-10 and TNF-α). Mechanistically, elevated UBD activated phosphorylated-p38 in RA-FLSs | no |
| XCL1    | yes                     | [https://doi.org/10.1016/j.joca.2010.08.003](https://doi.org/10.1016/j.joca.2010.08.003) | this chemokine shows reduced level in SF of RA patients compared to healthy; this chemokine stimulates migration of human mesenchymal progenitors from bones | no |
| ZBED2   | no                      |        |                                               | no |
| PLA2G2D | not really              |        | immunosuppressive activity, mentioned in the context of psoriatic arthritis | no |

