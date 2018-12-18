<p># DataEngineerTest<br />Step 0<br />Clone this repo and commit your work into the local copy. (You will not push your work to the GitHub repo)<br />Step 1<br />Connect to AWS MySQL RDS instance bcbsnc-de-test.crlleswktbdf.us-east-1.rds.amazonaws.com<br />Database name:'detest'<br />Credentials username:'guest' password:'***from BC rep***'</p>
<p>Step 2<br />Write a program using any language to automate this DDL treatment of Apache HIVE reserved words<br />{<br /> Read list of hive reserved words from the reserved_word_list table to build a list/dictionary you will need<br /> Use a string match or lookup function and replace/modify all column names that are reserved words<br /> with the same name surrounded by '_'<br /> e.g. TABLE =&gt; _TABLE_<br /> Use a string replace / lookup to replace/modify all special characters (' ', '\', '/', '@', '%') with '_'<br /> e.g. steps/minute =&gt; steps_minute<br />}</p>
<p>Step 3<br />Write a program using any language to automate this DDL treatment of Apache HIVE data types<br />{<br /> Build a list of valid hive data types into a list/dictionary you will need<br /> Use a string match or lookup function and replace/modify all mysql data types to hive supported types<br /> e.g. char(20) =&gt; string<br />} <br /> <br />Step 4<br /> Read the existing schema/metadata for the table named 'source_table' (Hint Get the create table script)<br /> Get the list of column names and data types<br /> <br />Step 5<br /> Run the column names through the reserved word checker function<br /> Run the data types through the data type checker function<br /> <br />Step 6<br /> Generate the HIVE compatible DDL for the table 'source_table'</p>
<p>Step 7<br /> Load the customer.json data file into the 'customer' data table in the detest mysql database<br /> Add just your initials into the 'initials' data column<br /> Use any language or tool. Take whatever action is required to complete the load. <br />Be able to explain the process and/or share the code<br /> <br />Submit<br /> A screnshot of your local repo commits..<br /> Your code for the DDL treatments.<br /> The HIVE DDL code you generated.<br /> The process / code used for the customer table load.</p>
