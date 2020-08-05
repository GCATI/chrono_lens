# chrono_lens

This is the public repository of our cloud hosted scalable pipeline that downloads data on a regular schedule, then analyses the data and stores detected feature counts in a database. Results are then analysed on a slower schedule where missing values are imputed, seasonal adjustment applied and then an underlying trend presented.

# Technologies Used

This pipeline was built with Google Cloud Platform, using:
* Cloud Functions (Python)
* Cloud Run (R)
* BigQuery

The analysis pipeline peaked at approximately 5,000 machine learning models running in parallel during testing, showing its scalability.
