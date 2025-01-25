Zhang et al. (2018) developed a convolutional neural network (CNN) that mimics visual processing through the human ventral pathway and adapted top-down modulation of the prefrontal cortex. They investigated whether this approach could predict human eye movements during visual search tasks. Notably, the model used zero-shot learning information about targets to apply top-down modulation, demonstrating that CNN models can find invariance in prior target stimuli and efficiently identify new targets within the same category in subsequent visual search tasks.

This project aimed to investigate how color features of the target cue influence visual search through top-down modulation, based on the previous research. Human behavioral experiments revealed delayed responses when colors of the pre-cue matched target or distractor stimuli, suggesting that color feature information influenced visual searches through bottom-up or top-down mechanisms.

A pretrained VGG16 model and visual search algorithm were used to analyze how top-down modulation of color information affects eye movement predictions.
Experiment 1 evaluated whether the model could replicate previous research results. It included two search display conditions:
- Target Identical: Search image contained a stimulus identical to the target cue (with 2D rotations or reflections to add variability)
- Target Different: Search target was from the same object category but visually distinct from the target cue

Experiment 2 included color conditions:
- Color Match: Search target had a color
- Color Mismatch: A distractor stimulus had a color
- Non-Match: No search stimuli had color
All trials in Experiment 2 ensured that the target cue stimulus never reappeared in the subsequent search task.
