# PySpark Data Processing Experiment

Welcome to my **PySpark Data Processing Experiment**! This repository showcases a small-scale project where I explored PySpark's capabilities for handling and transforming large datasets. The goal was to preprocess a synthetic dataset with 50 million records and gain hands-on experience with distributed data processing tools.

---

## Project Overview

### Features:
- **Synthetic Dataset Creation**:
  - 50 million records with columns like age, salary, gender, country, and purchase decisions.
  - Realistic challenges like missing values and 'unknown' entries.

- **Data Cleaning & Transformation**:
  - Filtered out invalid entries.
  - Replaced missing values with column averages.
  - Cast data types to ensure schema accuracy.

- **Output**:
  - Cleaned and transformed data written into a new CSV file, ready for further analysis or machine learning workflows.

---

## Getting Started

### Prerequisites
- Python 3.7+
- Apache Spark 3.5.4
- JDK 11
- Required Python libraries:
  ```bash
  pip install pandas numpy tqdm findspark
  ```

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pyspark-data-processing.git
   cd pyspark-data-processing
   ```

2. Install required dependencies:
   ```bash
   pip install pandas numpy tqdm findspark
   ```

3. Generate the synthetic dataset:
   - Adjust `TOTAL_RECORDS` or `CHUNK_SIZE` parameters in `data_processing_with_pyspark.py` if needed.
   ```bash
   python data_processing_with_pyspark.py
   ```

4. Process the dataset using PySpark:
   ```bash
   python data_processing_with_pyspark.py
   ```

5. View the output:
   - The transformed data will be saved in the `bank_prospects_transformed` directory.

---

## Directory Structure
```plaintext
pyspark-data-processing/
├── data_processing_with_pyspark.py  # Main script
├── README.md                        # Project documentation
├── Bank_data.csv                    # Synthetic dataset (generated)
├── bank_prospects_transformed/      # Transformed data output
```

---

## Key Learnings
- Practical understanding of PySpark for distributed data processing.
- Handling large datasets efficiently.
- Data cleaning and typecasting in a scalable framework.

---

## Next Steps
- Integrating advanced PySpark functionalities, such as Spark MLlib for machine learning workflows.
- Exploring real-time data processing with Spark Streaming.

---

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the repository.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- Inspired by my learning journey in Big Data and PySpark.
