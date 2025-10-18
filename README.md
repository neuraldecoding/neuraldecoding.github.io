# Neural Decoding Research

Research fokus on Visual Neural Decoding Research

Background: 
* *a vital capability for vision restoration via brain-computer interfaces.*
* *Understanding neural mechanisms is critical for discerning the nature of brain disorders and enhancing treatment methodologies*
* *For humans vision is the dominant contributor to the interaction between the external environment and the brain(Yu2025Robust)*

Team:
* Rolly Maulana Awangga -- rollymaulanaa@student.telkomuniversity.ac.id
* Prof. Dr. SUYANTO S.T., M.Sc. -- suyanto@telkomuniversity.ac.id
* Bedy Purnama, S.Si., M.T., Ph.D. -- bedypurnama@telkomuniversity.ac.id

Links:
1. [Systematic Mapping Study](/sms)
2. [Systematic Literature Review](/slr)
3. [Preliminary Research](/pr)

## Executive Summary

Systematic Mapping Study

### Hasil Workflow

<div class="mermaid">
flowchart TD
    A["140 dokumen<br>Sebelum deduplikasi:<br><a href='/sms/bibtex/scopus.bib' target='_blank'>• Scopus: 88</a><br><a href='/sms/bibtex/ieee.bib' target='_blank'>• IEEE: 52</a>"]
    B["118 dokumen<br>(Setelah hapus duplikat)"]
    C["~70-80 dokumen<br>(Setelah screening title/abstract)"]
    D["~40-50 dokumen<br>(Setelah full-text review)"]
    E["~30-40 dokumen<br>(FINAL untuk analisis)"]
    
    A --> B --> C --> D --> E

    click B "https://neuraldecoding.github.io/sms/bibtex/" _blank
	click C "https://neuraldecoding.github.io/sms/screening/" _blank
</div>

Langkah: 
1. Export dari Scopus → [format BibTeX](/sms/bibtex/scopus.bib)
2. Export dari IEEE → [format BibTeX](/sms/bibtex/ieee.bib)  
3. Upload ke [tools bibtex cleaner and validation](https://colab.research.google.com/drive/1dK1OTfULLtE1d9Gd-a5iWjef9h8PjUD2?usp=sharing) untuk dua file tersebut
4. Jalankan [tools](https://colab.research.google.com/drive/1dK1OTfULLtE1d9Gd-a5iWjef9h8PjUD2?usp=sharing) hingga hasil akhir deduplikasi sudah di dapatkan
5. Review manual untuk duplikat yang terlewat

Tools validasi dan deduplikasi referensi
```url
https://colab.research.google.com/drive/1dK1OTfULLtE1d9Gd-a5iWjef9h8PjUD2?usp=sharing
```

