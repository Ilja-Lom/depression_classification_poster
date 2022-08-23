# |
# <strong>Automated Depression Classification Using Speech</strong>

# <strong>Methods</strong>
## Why were only Scripted recordings selected?
Only the speech recordings based on scripted text were used for training, and testing the models. This was to reduce the sample size; unscripted speech is much more variable, so the model will have to be exposed to a greater sample size to extract meaningful information for classification. However, the disadvantage with this approach is the loss of natural expression that is part of speech and could be useful in classifying depression.

## Why were only English-spoken recordings selected?
To ensure the data is homogenous, with reduced variation, only recordings in English were selected. This helps minimise the sample size required for the models to train; additionally, it removes uncontrolled-for variables between languages.

# <strong>Conclusions</strong>
## Limitations
### Mel-Spectrogram
One of the limitations of the research is the use of the Mel-Spectrogram. I do not believe that it offers sufficient information for accurate depression classification, because depression manifests itself very ambiguously in speech, and varies from person to person. For this task, I believe more informative data is required in the form of feature engineering, which allows the machine learning model to be more selective of the data.

### Temporal Modelling
A potential reason for the lacklustre performance of the CNN-LSTM model is that the time-frames were too large. Each speech recording was split into 7 segments. Perhaps for more optimal CNN-LSTM performance, the frames must be of smaller size.

## Future Research
As evident in the results of the model, there is a significant trade-off between depressed, and non-depressed classification when using a single model. An ensemble approach which incorporates many model variations is likely to help create a more robust overall model. There is a possibility however, that the data processing technique used, inherently does not perform well for depression classification. Future research should compare model performance between fully-automated pipelines, and conventional approaches using feature engineering.





