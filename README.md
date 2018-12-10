# SepsisMIMIC
Sepsis prediction during ICU Stays

Follow this instructions to get the final predictive modeling for Sepsis Benchmarking of ICU Stays from MIMIC III database.

- Download all csv from MIMIC III, build the postgreSQL database with the give code from MIMIC.
mimic-code/buildmimic/postgres

- to be filled: sql
- to be filled: python

- Follow the ETL_04_output.csv result from last step, Spark Dataframe with scala was used to perform feature construction. 
 Follow the zeppelin notebook to get the final trainable dataframe. It will automatically save the csv to get the final trainable dataset.
 \- Environment: Spark DataFrame with Scala. 
 \- Zeppelin note: Feature_Construction_ETL_04.json
 \- Use the Zeppelin to import the above json file to get the runnable note. 
 \- Remember to change the file path of ETL_04_output.csv in the first block of zeppelin notebook.
    **The actual csv are provided in this repository (H0, H1, H2, H3, H4, H5, H24)**
- Implement the jupyter notebook for final predivtive modeling.
