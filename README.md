# TCDF-mod
TCDF modification made as the result of the internship of Mukhtar Urubassyrov from Bell labs, France. 

# TCDF modifications 
## Fixed features:
  \item depth-wise separable convolution interpretation
  \item added residual connection for first layer
  \item number of hidden layers parameter
  \item (code) ground truth input notation
  \item (code) incorrect data shape casts (\texttt{squeeze} methods)

## New added features

    \item weight visualization
    \item input normalization
    \item option to add different interventions for testing purposes
    \item pandas dataframe support added

## Reworked
    \item metrics and logging
    \item delays calculation
    \item repetitive neural net model structure simplification



# Some results 
1.     delay discovery method might experience several issues as using weight back propagation is a conceptually different problem
2.    instantaneous effects identification stays unclear as direction is the only important detail here and we do not know how NN can distinguish this behaviour
3. validating an intervened dataset does not make any sense when model learns wrong directions or connections

# Future work 
We are inspired by further work and collaboration with Jakob Runge, whose work inspired us to continue working on this project and modify the testing phase 
See some of the presentations and work from Jakob here https://www.youtube.com/watch?v=_9ltYj7Ler8&t=1439s and https://scholar.google.com/citations?user=wtXVvuUAAAAJ&hl=en
