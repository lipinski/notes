# Anomaly detection
## Definition

Anomalies are a subset of outliers (Aggarwal 2013)
* All observations = normal data + outliers
* Outliers = noise + anomalies
* Noise = uninteresting outliers
* Anomaly = sufficiently interesting outlier

## Types of anomalies
* Point anomalies - an individual data point seems strange when compared with
the rest of the data. Example: an unusually large credit card purchase
* Contextual anomalies - the data seems strange in a specific context, but not
otherwise. Example: a US credit card holder makes a purchase in Japan
* Collective anomalies - a collection of data points seems strange when compared
with entire dataset, although each point may be OK. Example: ten consecutive
credit card purchases for a sandwich at hourly intervals

## Tools

### Statistics
- Cumulative distribution function (CDF)
- Probability distribution
- Statistical tests: 
  - z-score 
  - y = (x - X) / MAD where: X - median, MAD = median(|x - X|) 
  - mahalanobis distance

