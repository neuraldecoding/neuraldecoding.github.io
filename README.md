# Neural Decoding Research

Research fokus on Visual Neural Decoding Research

Background: 
* *a vital capability for vision restoration via brain-computer interfaces.(Peng2025Decoding)*
* *Understanding neural mechanisms is critical for discerning the nature of brain disorders and enhancing treatment methodologies(Shakeripour2025Object)*
* *For humans vision is the dominant contributor to the interaction between the external environment and the brain(Yu2025Robust)*

Team:
* Rolly Maulana Awangga -- rollymaulanaa@student.telkomuniversity.ac.id
* Prof. Dr. SUYANTO S.T., M.Sc. -- suyanto@telkomuniversity.ac.id
* Bedy Purnama, S.Si., M.T., Ph.D. -- bedypurnama@telkomuniversity.ac.id

Tahapan:
1. Validitas Data : Tema : [Harmonisasi data EEG](https://www.sciencedirect.com/science/article/pii/S1388245724002785) (Wajib data valid sebelum masuk ke Neural Decoding).
2. Preprosesning [Riemannian Geometry](https://ieeexplore.ieee.org/document/10748767).Riemannian Tangent Space + SVM. xDAWN, CCA.
3. Benchmark Tools: [MOABB](https://iopscience.iop.org/article/10.1088/1741-2552/aadea0) dan [SpeechBrain-MOABB](https://www.sciencedirect.com/science/article/pii/S001048252401182X)
4. Mamba Based EEG Decoding: [CBraMod](https://github.com/wjq-learning/CBraMod) dan [EEGMamba](https://github.com/wjq-learning/EEGMamba)
5. Klasifikasi atau Rekonstruksi :  Neural Decoding pada Wearable BCI(EEG)

Metode Klasik:
* Jika berurusan dengan Motor Imagery: Raw EEG langsung diolah jadi Matriks lalu masuk Riemannian.
* Jika berurusan dengan P300 (Visual/Auditory): Raw EEG disaring dulu oleh xDAWN, baru masuk Riemannian.
* Jika berurusan dengan SSVEP (Visual Kedip): Raw EEG langsung diolah dengan CCA (tidak pakai Riemannian sama sekali).


Paper Review:
1. [Neural decoding for EEG-BCI: from conventional machine learning to deep learning models](https://www.sciencedirect.com/science/article/pii/S2589238X26000021)
2. [Deep Neural Networks and Brain Alignment: Brain Encoding and Decoding (Survey) (Oota, arxiv, 2024)](https://arxiv.org/abs/2307.10246)

[Generative AI Rule](/gen-ai)

Target Semester 1:
1. [Systematic Mapping Study](/sms)
2. [Systematic Literature Review](/slr)
3. [Preliminary Research dengan dataset publik](/pr)
   * [MindBigData Web](https://mindbigdata.com/opendb/index.html), [Leaderboard](https://huggingface.co/spaces/DavidVivancos/MindBigData-Leaderboard), [github repo](https://github.com/klankey/Brain_to_Image), [Hugging Face](https://huggingface.co/datasets/DavidVivancos/MindBigData2022), [Huggingface EP](https://huggingface.co/datasets/DavidVivancos/MindBigData2022_MNIST_EP)
   * [BNCI Horizon](https://bnci-horizon-2020.eu/database/data-sets)
   * [nilearn miyawaki](https://nilearn.github.io/dev/modules/description/miyawaki2008.html)
   * [van gerven dataset](https://www.sciencedirect.com/science/article/pii/S1053811920310879)

## Executive Summary

Referensi

### Hasil Workflow

<div class="mermaid">
flowchart TD
    A["140 dokumen<br>Sebelum deduplikasi:<br><a href='/sms/bibtex/scopus.bib' target='_blank'>• Scopus: 88</a><br><a href='/sms/bibtex/ieee.bib' target='_blank'>• IEEE: 52</a>"]
    B["118 dokumen<br>(Setelah hapus duplikat)"]
    C["67 dokumen<br>(Yang bisa di akses)"]
    D["54 dokumen<br>(Subjek Manusia)"]
    E["53 dokumen<br>(Neural Decoding Langsung)"]
	F["53 dokumen<br>(Full-text review)"]
    
    A --> B --> C --> D --> E --> F

    click B "https://neuraldecoding.github.io/sms/bibtex/" _blank
	click C "https://neuraldecoding.github.io/slr/screening/" _blank
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

