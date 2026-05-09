# Zetzoho-Yuhmu-Speech-Dataset

This repository presents a dataset oriented toward the study of low-resource languages, using the Yuhmu language (an Otomí variant) as a case study. The dataset is designed to support research in automatic speech recognition (ASR) and pronunciation analysis in scenarios with limited linguistic data.

The dataset is composed of acoustic embeddings derived from word-level audio samples, capturing relevant phonetic features for pronunciation analysis. These embeddings provide a compact representation of speech information, facilitating their use in machine learning models.

The data is organized into two main categories: correct pronunciation and incorrect pronunciation, enabling experimentation in supervised classification tasks, automatic pronunciation assessment, and phonetic variability analysis. This structure allows the identification of discriminative patterns between well-formed and mispronounced speech.

This dataset has been designed and used for experimentation in pronunciation analysis, particularly in low-resource language scenarios, where data scarcity and linguistic variability represent significant challenges. In this context, acoustic embeddings contribute to improving speech representation and support the development of robust models.

Additionally, this resource provides a foundation for developing systems aimed at pronunciation feedback in language learning processes, as well as for strengthening efforts in the preservation and documentation of indigenous languages in Mexico.

## Authors

- Eric Ramos-Aguilar  
- J. Arturo Olvera-López
- Ivan Olmos-Pineda 
- Ricardo Ramos-Aguilar
- Daniel Sánchez-Ruiz

## Dataset Contents

- Correct pronunciation embeddings: **5835 samples**  
- Incorrect pronunciation embeddings: **2620 samples**  
- Audio samples of words with correct pronunciation: **100 samples**  
- Audio samples of words with incorrect pronunciation: **100 samples**  

These resources enable comparative analysis between correct and incorrect phonetic realizations, supporting experimentation in classification and automatic pronunciation evaluation tasks.

## t-SNE Embeddings Visualization

<img width="711" height="553" alt="t-SNE representation" src="https://github.com/user-attachments/assets/01e2f2b1-87b9-4ecb-b1a8-6d6e31f1b199" />

## Associated Paper

https://www.cys.cic.ipn.mx/index.php/CyS/article/viewFile/5912/4055

## Citation

If you use this dataset, please cite:

```bibtex
@article{ramos2025yuhmu,
  title={Yuhmu Database: A Corpus of Tonal Speech Lacking Conventional Writing},
  author={Ramos-Aguilar, Eric and Olvera-L{\'o}pez, J Arturo and Olmos-Pineda, Ivan},
  journal={Computación y Sistemas},
  volume={29},
  number={3},
  year={2025}
}
```

## License

© 2025 Eric Ramos-Aguilar et al.

This dataset is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** License.

You are free to:
- Share — copy and redistribute the material  
- Adapt — remix, transform, and build upon the material  

Under the following terms:
- Attribution — You must give appropriate credit to the original authors  
- NonCommercial — You may not use the material for commercial purposes  

This dataset is intended for research and educational use, particularly in the study of low-resource languages.

For more details: https://creativecommons.org/licenses/by-nc/4.0/

For commercial use or special permissions, please contact the authors:  
Eric Ramos Aguilar ([eramosa@ipn.mx](mailto:eramosa@ipn.mx))  
Ricardo Ramos Aguilar ([rramosa@ipn.mx](mailto:rramosa@ipn.mx))
