# ID mappings
We used different IDs in different phases to identify the units of study. Traceability information is provided below.

* `01_Corpus_full.xlsx`
  * Key: `BibtexKey`
* `02_Primary_studies_included.xlsx`
  * Key: `SID` (as in: Study ID)
  * Reference to `01_Corpus_full.xlsx`: `BibtexKey`
* `03_Clusters.xlsx`
  * Key: `ClusterID`
  * Reference to `02_Primary_studies_included.xlsx`: `SID`
  * Reference to `01_Corpus_full.xlsx`: `BibtexKey`
* `04_Primary_studies_clustered_with_PID.xlsx`
  * Key: `PID` (as in: Public ID)
  * Reference to `03_Clusters.xlsx`: `ClusterID`
  * Reference to `02_Primary_studies_included.xlsx`: `SID`
  * Reference to `01_Corpus_full.xlsx`: `BibtexKey`