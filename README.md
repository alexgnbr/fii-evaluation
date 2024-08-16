# fii-evaluation

This project aims to evaluate Fundos Imobiliários - FIIs (similar to American REITs) and present them with objective values.

The main idea was to choose some interesting metrics and develop a solution that would make it easy to analyze and compare FIIs.

A simple approach was to measure with a score from 0 to 10 but some metrics have different scale values, so I designed a method using percentiles and coefficients to balance the score.

The dash framework was used for presentation with HTML controls to filter the funds and set the weight of the metrics, a table to show the score and charts to compare metrics and funds.