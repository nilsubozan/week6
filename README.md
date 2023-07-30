# File Ingestion and Schema Validation

We processed a large CSV/Text file (2+ GB) using various Python libraries: pandas, Dask, Modin, and Ray. We measured the computational efficiency of each method. The data columns were validated by removing special characters and white spaces. We created a YAML file to store the column names and separator. We confirmed the data's integrity by checking it against the YAML file. The processed data was written to a pipe-separated text file in gzip format. The summary included the total rows, total columns, and file size.
