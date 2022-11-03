# Matching methods for causal inference with time-series cross-sectional data

📍 virtual MZES, Mannheim

📆 October 05, 2022

Matching methods improve the validity of causal inference by reducing model dependence and offering intuitive diagnostics. While they have become a part of the standard tool kit across disciplines, matching methods are rarely used when analyzing time-series cross-sectional data. We fill this methodological gap. In the proposed approach, we first match each treated observation with control observations from other units in the same time period that have an identical treatment history up to the pre-specified number of lags. We use standard matching and weighting methods to further refine this matched set so that the treated and matched control observations have similar covariate values. Assessing the quality of matches is done by examining covariate balance. Finally, we estimate both short-term and long-term average treatment effects using the difference-in-differences estimator, accounting for a time trend. We illustrate the proposed methodology through simulation and empirical studies. An open-source software package is available for implementing the proposed matching methods.

📝 [Slides](https://github.com/SocialScienceDataLab/matching-methods-causal-inference/blob/main/matching-methods-causal-inference.pdf)

👤 [Erik H. Wang](https://erikhw.github.io/) is an Assistant Professor in the Department of Political and Social Change (PSC) at the Australian National University. His research interests center on historical political economy, politics of state-building, and bureaucracy as well as statistical methods of causal inference.



