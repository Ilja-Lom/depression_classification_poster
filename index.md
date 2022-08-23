# |
# Automated Depression Classification Using Speech
# |

# Methods
## Why were only Scripted recordings selected?
Only the speech recordings based on scripted text were used for training, and testing the models. This was to reduce the sample size; unscripted speech is much more variable, so the model will have to be exposed to a greater sample size to extract meaningful information for classification. However, the disadvantage with this approach is the loss of natural expression that is part of speech and could be useful in classifying depression.

## Why were only English-spoken recordings selected?
To ensure the data is homogenous, with reduced variation, only recordings in English were selected. This helps minimise the sample size required for the models to train; additionally, it removes uncontrolled-for variables between languages.

# Conclusions
## Future Research
As evident in the results of the model, there is a significant trade-off between depressed, and non-depressed classification when using a single model. An ensemble approach which incorporates many model variations is likely to help create a more robust overall model. There is a possibility however, that the data processing technique used, inherently does not perform well for depression classification. Future research should compare model performance between fully-automated pipelines, and conventional approaches using feature engineering.





