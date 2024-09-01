<h1>PySpark SQL Assignment Summary</h1>
    <p>This document provides an overview of the tasks performed using PySpark SQL in the Google Colab environment.</p>

  <h2>1. Environment Setup</h2>
    <p>
        We started by setting up the Spark environment in Google Colab. This involved:
        <ul>
            <li>Installing Java and Spark.</li>
            <li>Configuring environment variables for Java and Spark.</li>
            <li>Starting a SparkSession.</li>
        </ul>
    </p>

  <h2>2. Data Processing</h2>
    <p>
        We performed several operations using PySpark SQL:
        <ul>
            <li>Read data from an AWS S3 bucket into a DataFrame.</li>
            <li>Created a temporary view of the DataFrame.</li>
            <li>Ran various SQL queries to analyze the data:
                <ul>
                    <li>Calculated the average price of four-bedroom houses sold per year.</li>
                    <li>Determined the average price of homes built in each year with specific criteria (number of bedrooms, bathrooms, etc.).</li>
                    <li>Calculated the average price of homes per "view" rating with price filtering and ordered the results.</li>
                </ul>
            </li>
        </ul>
    </p>

  <h2>3. Caching and Performance</h2>
    <p>
        We cached the temporary table and reran a query to evaluate performance improvements:
        <ul>
            <li>Cached the temporary table and ran a query to check performance improvements.</li>
            <li>Saved the DataFrame as partitioned parquet files.</li>
            <li>Read the parquet files and created a new temporary view for further querying.</li>
        </ul>
    </p>

   <h2>4. Cache Management</h2>
    <p>
        Finally, we managed the cache:
        <ul>
            <li>Uncached the temporary table.</li>
            <li>Verified that the table was no longer cached.</li>
        </ul>
    </p>

   <h2>5. Performance Measurement</h2>
    <p>
        We measured the runtime for specific queries to analyze performance before and after caching.
    </p>

   <p>For more details, refer to the code snippets provided in the Jupyter Notebook.</p>
