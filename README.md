# BERT and RoBERTA

T5 – Text-to-Text Transfer Transformer (Google) for emotion recognition on text

## Emotion Models

Discrete Emotion Models (DEM) – distinct classes(independent)

- Ekman
- Plutchik
- Orthony, Clony, Collins

Dimensional Emotion Models (DEM) – distinct classes(dependent)

- Russel
- Plutchik

## Detection Approaches

- Lexicons
- ML
- DL
  - RNN
  - F-RNN
  - CNN
  - _TRANSFORMERS_
- Hybrid
  - DL – state of the art, i.e. T5-_TRANSFORMERS_ (e.g. BERT, RoBERTA)

## T5-Methodolgy

For BERT requirements, create on own GPU environment and pip install:

- Python=3.6
- Tensorflow-gpu==2.1
- PyTorch==1.3.1 cudatoolkit=10.1
- Transformers==2.9.0
- PyTorch-lightning==0.7.5

## Conclusion

- with a large dataset can achieve accuracy of 98.8%

## Dataset

- dropbox.csv

## Further improvements

- Get better and bigger dataset with equal number of classes on dropbox.csv
- Finalize on RoBERTA methodology
- Include into huggin face T5-library to be able to use dataset directly
- Integrate automatic data collection on T5-methodologies
- Convert into other classes of systems (TP, DEM, T5)
- Hybridize methodologies with Lexicons, and ML

## Future

- CI+D of emotion recognition in speech and videos/images