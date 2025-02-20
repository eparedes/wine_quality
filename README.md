# How Good Is This Wine?
### Overview
As a wine maker, it would  be valuable to predict the perceived quality of a wine given its checmical composition, e.g. acidty, alcohol, tanins, etc.
With this information, wine makers could decide how to further process a wine based on its predicted quality, e.g. wines with higher quality could be botteled using more expensive materials to preserve the quality for longer, or decide exactly where a given wine will be distribuited, e.g. high end retail stores vs more general groceries stores. This kind of insights could mean maximizing profits and/or reducing operational costs. 


A model that predicts the quality of a wine given its chemical composition was developed for this process. Several classificators were evaluated and the one who yield the highest accuracy was selected. Additionally, ensemble techniques were explored to ensure the highest accuracy could be obtained with either a singular model or an ensemble.

### Data
The data to train and test the models was obtained from https://archive.ics.uci.edu/dataset/186/wine+quality

The data consists of two .csv files, one containing red wine data and the other one containing white wine data. It is worth noting that this data pertains to Portuguese "Vinho Verde" wine, so the model should be retrained with wine data from other reigions to better generalize the quality scores.