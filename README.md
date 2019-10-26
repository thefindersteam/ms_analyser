# **Tranquility score** calculation

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thefindersteam/ms_analyser/blob/master/tranquility_score_calc.ipynb)

## Objectives

- reliably determine valid increases in long-term stress levels
- distinct between valid stress increase (alert) and false positive (log and learn)
- classify into 3 types of MS (eventually)


## Libraries
- NumPy, SciPy, Keras, TensorFlow, Pandas
- [HeartPy](https://pypi.org/project/heartpy/)
- [Python waveform-database (WFDB)](https://wfdb.readthedocs.io/en/latest/)
- [Python Heart Rate Analysis Package](https://github.com/paulvangentcom/heartrate_analysis_python)

### Data sources
- [HeartPy sample data](https://python-heart-rate-analysis-toolkit.readthedocs.io/en/latest/heartpy.heartpy.html#heartpy.load_exampledata)
- [PhysioNet wrist PPG excercise dataset](https://physionet.org/content/wrist/1.0.0/)
- [BIDMC PPG and Respiration Dataset](https://physionet.org/content/bidmc/1.0.0/)

### References
- Oura HRV [basics](https://ouraring.com/heart-rate-variability-basics/), [details](https://ouraring.com/how-to-measure-heart-rate-variability/) and [white paper](https://d1a0efioav7lro.cloudfront.net/wp-content/uploads/2018/10/23112753/The-HRV-of-the-Ring-Comparison-of-OURA-Ring-to-ECG.pdf)
- [An innovative peak detection algorithm for photoplethysmography signals: an adaptive segmentation method](https://www.researchgate.net/publication/299593684_An_innovative_peak_detection_algorithm_for_photoplethysmography_signals_An_adaptive_segmentation_method)
- [Assessing mental stress from the photoplethysmogram: a numerical study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5964362/)
- [Stress and Heart Rate Variability: A Meta-Analysis and Review of the Literature](https://www.ncbi.nlm.nih.gov/pubmed/29486547)
