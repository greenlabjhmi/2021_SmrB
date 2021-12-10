# 2021_SDASD

The codes to process and analyze FASTQ files for Tn-seq screening, 5'RACE-seq, and 3'RACE-seq in "Ribosome collisions induce mRNA cleavage and ribosome rescue in bacteria". First run codes for processing, then run codes for plotting.

Folder "StallReporters" contsins FASTA files of SecM and EPstop reporters. 

Folder "TnSeq_WIG" contsin WIG files for Tn-seq.
* ks193 - Initial library
* ks195 - Bleomycin resistant colonies from SecM reporter

Folder "RACE_WIG" contains WIG files for RACE-seq
* ks222 - 5RACE on SecM reporter in WT strain
* ks223 - 5RACE on SecM reporter in ∆tmRNA strain
* ks224 - 5RACE on SecM reporter in ∆smrB strain
* ks225 - 5RACE on SecM reporter in ∆∆ strain
* ks230 - 5RACE on EPstop reporter in WT strain
* ks231 - 5RACE on EPstop reporter in ∆tmRNA strain
* ks232 - 5RACE on EPstop reporter in ∆smrB strain
* ks233 - 5RACE on EPstop reporter in ∆∆ strain
* ks246 - 3RACE on SecM reporter in WT strain
* ks247 - 3RACE on SecM reporter in ∆tmRNA strain
* ks248 - 3RACE on SecM reporter in ∆smrB strain
* ks249 - 3RACE on SecM reporter in ∆∆ strain
* ks254 - 3RACE on EPstop reporter in WT strain
* ks255 - 3RACE on EPstop reporter in ∆tmRNA strain
* ks256 - 3RACE on EPstop reporter in ∆smrB strain
* ks257 - 3RACE on EPstop reporter in ∆∆ strain

### Dependencies
* skewer-0.2.2
* cutadapt-1.16
* bowtie-1.1.2
* python-2.7
* Anaconda2-5.0.1
* numpy-1.14.0
* pandas-0.24.2
* matplotlib-2.2.5
* seaborn-0.9.1
* Jupyter notebook
