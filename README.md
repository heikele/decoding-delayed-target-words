# Sempred-Decoding

__Summary__
The aim of this experiment was to test whether we could decode semantic category of a delayed target word, whose category was highly predictive based on the preceding sentence context, prior to its presentation and during the delayed time period (pause). In the first experiment we chose abstract vs. concrete as the class category for decoding. We also tested whether the analysis pipeline could decode isolated auditory and visual words (abstract vs. concrete).

In a second experiment we chose animate vs inanimate as the class category for decoding, repeating the first stage of experiment 1 by decoding the semantic category of a delayed target word prior to its presentation.

ERP analysis was done using spatiotemporal permutation t-test on sensor data. No significant differences were observed for the delayed target words during the delayed time window (absract vs. concrete and animate vs. inanimate; experiment 1 and 2, respectively). Significant differences were observed for the isolated auditory and visual words.

Generalization across time (GAT) decoding showed significantly above chance decoding for all comparisons. Linear SVM and GAT was able to significantly above chance decode abstract vs concrete delayed target words during the pauses prior to the presentation of the target word. The classifier was able to significantly decode above chance abstract vs. concrete isolated auditory and visual words.  Furthermore, in experiment 2, classifiers were able to significantly decode above chance animate vs. inanimate delayed target words from the neurophysiological responses during the delayed time window (prior to target word presentation).

All analysis was based on electroencephalography (EEG) recorded data and two sets of 35 participants (n=35 in each experiment).

In experiment 1 150 stimuli were used in each modality (n=75 per condition) and 108 stimuli were used in experiment 2 (n=54 per condition).

__Experiments:__
- Experiment 1: 
          A. delayed concrete/abstract target nouns, 
          B. concrete/abstract target nouns in auditory word lists
          C. concrete/abstract target nouns in visual word lists
          
- Experiment 2:delayed animate/inanimate target nouns)  

__Analyses:__
- ERP analysis using spatiotemporal permutation t-test on sensor data
- MVPA decoding over time using generalization across time using a linear SVM
