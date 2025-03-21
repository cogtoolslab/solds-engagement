## 2023 Dataset 

In this folder:

`college-23`: *select* files from the coursekata internal-research college-23 directory (only necessary ones to keep this streamlined).

`college-23-processed`: *processed* versions of the files from coursekata college-23

`codebooks`: probably not needed to process 2023 data, includes information about all textbook versions and classes

<!-- 
`codebook_all_surveys_updated.csv`: codebook for processing surveys (NB: this is taken from coursekata internal-research repo but is not part of the college-23 repository) -->

```
├── codebooks/
    ├── codebook_institutions.csv
    ├── codebook_page_updated.csv
    └── codebook_page.csv
├── college-23/
    ├── codebooks/
        ├──survey-codebooks/
            ├── codebook_all_surveys_updated.csv
            └── codebook_all_surveys.csv
        ├── codebook_chapter.csv
        ├── codebook_page_pageviews.csv
        └── codebook_page.csv
    ├── raw/
        ├── media_views.Rdata
        ├── page_views.Rdata
        └── responses.Rdata
    └── classes.csv
```