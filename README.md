The proBatch package contains functions for diagnosing and removing
    batch effects and other unwanted variation in high-thoughput experiment, primarily
    designed for DIA proteomics data.
    The diagnostic part of the package can be broadly divided in (1) Genome-wide
    and (2) Gene-specific functions, explained in corresponding vignettes. Since 
    the diagnostic part for batch effects does require batch effect removal, here
    we provide a few convenience wrappers for common batch-effect removal approaches,
    namely, ComBat (Johnson et al. 2007 Biostatistics) and mean/median centering.
    However, proteomics data may require more complicated technical artifact 
    correction approaches like non-linear fitting, which is also found in "normalization"
    section of this package. 
    The approaches are described in (Čuklina et al. 2019, MCP)
