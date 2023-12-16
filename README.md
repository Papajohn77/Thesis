# Radius Query Performance Benchmarking

In the last few years, there has been a rise in Location-based services (LBS) applications that
utilize geospatial data to offer personalized services based on the user’s real-time location.
In user-facing applications, low latency is crucial for a seamless user experience (UX). The
choice of a spatial database heavily influences the performance of a location-based services
(LBS) application, hence becoming a critical decision. To ensure an unbiased and informed
decision, it is common practice to perform a database benchmark. In this study, we
conducted a benchmark to identify the most efficient spatial database among PostgreSQL
with the PostGIS extension and MongoDB in radius queries. The results indicate the
performance superiority of PostGIS over MongoDB in all the evaluated scenarios. One of the
key aspects of this study is that the benchmark conducted is fully reproducible to allow for
independent verification of the results and promote the advancement of knowledge in the
field.

The code repositories used to conduct the benchmarks can be found [here](https://github.com/orgs/Radius-Query-Performance-Benchmarking/repositories)
