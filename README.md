# SLR

This is a quick draft README to assist with setting everything up for finalizing stage 2 and moving on w/ the data extraction, synthesis and documentation sections :P


## Quick Setup & Start

1. **Ensuring Access**
    - Make sure you have access to the [shared Excel sheet](https://numcmy-my.sharepoint.com/:x:/r/personal/efyms24_nottingham_edu_my/Documents/QCNN_HQCNN_Screening_Stage2_WIP.xlsx?d=w6bd9652349f34315b62e84bab11cb451&csf=1&web=1&e=ncYMWu), Google Drive link, and access to this repo (if you can see this then you do!)
2. **Zotero Installation:**
    - Download [Zotero](https://www.zotero.org/download/) and the Zotero Connector.
3. **Google Drive File Imports**
    - Import all the files from the File Dump directory and extract them as necessary.
        - You'll need to extract files.zip from SLR-Stage2-WIP as it had to be zipped before adding it in comparison to the other directories.
4. **Extraction Verification**
    - Once everything is extracted it should be in the following format:

    ```LaTeX
    File Dump/
    │
    ├─ SLR-Stage2-WIP/
    │              ├── SLR-Stage2-zip.bib
    │              └── files.zip 
    │
    ├─ SLR-Stage2-EC8/
    │              ├── SLR-Stage2-EC8-PaywallExclusion.bib
    │
    └─ SLR-Stage2-ExcludedPapers/
                    ├── SLR-Stage2-ExcludedPapers.bib
                    └── files/
    ```

5. **File Movement [Needed for Zotero Imports]**
    - Once you extract it, move the files folder to be in the same directory as its respective .bib file to match the format of **SLR2-Stage2-ExcludedPapers**.
6. **Collection Creation in Zotero**
    - From there, open up Zotero and click on New Collection and create one named SLR-Stage2:

    <details>
    <summary>Visual Step #01:</summary>

    [![image.png](https://i.postimg.cc/7hKjMgxN/image.png)](https://postimg.cc/jnJ8RnnW)

    </details> <br>
7. **File Import in Zotero**
    - Click on File > Import.. > A file (bibTeX, RIS, Zotero RDF, etc.) > Next, then select the .bib of the respective folder you're extracting.

    <details>
    <summary>Visual Step #02:</summary>

    [![image.png](https://i.postimg.cc/Y9TBJNcf/image.png)](https://postimg.cc/62VPZvpy)

    </details> <br>
8. **Repeating Step 7**
    - Repeat this step for all three folders and organize them as appropriate.
9. **Verification of Import Status & File Count**
    - Verify that the total adds up to 270 (Excluded Papers + Paywalled Exclusions + WIP)
        - At the time of writing this README its at [15+54+201=270]

    <details>
    <summary>Visual Step #03:</summary>

    [![image.png](https://i.postimg.cc/wM540D9q/image.png)](https://postimg.cc/tnTzgZ1w)

    </details> <br>

10. **Stage 2 Steps :D**
    - Refer to the [*PICOC_RQs_ICsECs_ReviewScope.md*](https://github.com/Proteus-Nell/SLR/blob/main/Reproducible%20Section/Step%200%20-%20Search%20Queries/PICOC_RQs_ICsECs_ReviewScope.md) file or the [shared Excel file](https://numcmy-my.sharepoint.com/:x:/r/personal/efyms24_nottingham_edu_my/Documents/QCNN_HQCNN_Screening_Stage2_WIP.xlsx?d=w6bd9652349f34315b62e84bab11cb451&csf=1&web=1&e=ncYMWu) for the ICs, ECs & PICOC/RQs and from there you can start working on Stage 2 :D
