<!---
Decision Science 1 Class - Exercise 3
# DS1_E3_Pandas
--->
## Pandas Dataframe and Methods

#### Objective
The purpose of this program is to read in data records from a delimited formatted data file (CSV) into a pandas dataframe for data cleaning, and some data aggregation (such as min, max, standard deviation, grouping).  Data explorations are\:</br>
\- Identifying indexes that help optimize operations on the dataframe data</br>
\- Handling missing data, removing irrelevant rows, and correcting wrong values

#### Tools Used
Required tools to run the program are :</br>
\- Jupyter Notebook (It is recommended to install full Python distribution with Anaconda Python distribtion) </br>
\- a csv file having columns\: first_name,last_name,company_name,address,city,province,postal,phone1,email,web,exam_1,exam_2,exam_3,dept,transcode

#### Program walk-through
- Read in the CSV file, and make a copy of dataframe (DF): <br/>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/e83aca25-701c-4646-9ee1-b11d0a9ab6b2" width="50%" height="50%" alt="Read in CSV file"  />
</td></tr></table>
</p>
</br>

- Perform data explorations: </br>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/f8fdd874-6766-4cb0-af75-480b70813e7d" width="50%" height="50%" alt="Read in CSV file"  />
</br>
</br>
<img src="https://github.com/user-attachments/assets/30ae08b2-ecd5-41f3-96b4-e94fa32824a5" width="50%" height="50%" alt="Read in CSV file"  />
</td></tr></table>
</p>
</br>

- List index of dataframe records: </br>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/477b9986-2b8d-4f3b-b1f0-e74005752b6c" width="50%" height="50%" alt="List index of records"  />
</td></tr></table>
</p>
</br>

- Remove unwanted records, and drops all records where exam 3 are null: </br>
<p style="border: 2px solid #000000; padding: 1px;">
<table><tr><td>
<img src="https://github.com/user-attachments/assets/e7e0f566-2187-4a04-b8df-02262a498195"  width="50%" height="50%" alt="List index of records" />
</td></tr></table>
</p>
</br>

- Handle missing data by change the value of NaN (nulls) to 49.0:</br>
<table><tr><td>
<img src="https://github.com/user-attachments/assets/7be4f7b1-dc5f-46a2-bd0c-3748217c83de" width="50%" height="50%" alt="Change the value of NaN (nulls) to 49.0" />
</td></tr></table>
</br>
