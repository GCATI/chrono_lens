# chrono_lens

This is the public repository of our Google Compute Platform (GCP) hosted pipeline that downloads data on a regular schedule, then analyses the data and stores detected feature counts in a database (in this case, BigQuery). Results are then analysed on a slower schedule where missing values are imputed, seasonal adjustment applied and then an underlying trend presented.
