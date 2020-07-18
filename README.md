# JIRA-Social-Repository-OracleDB
This repository is a migration by product  to Oracle DB 11g from the PostGreSQL based database jira-social-repository (https://github.com/marcoortu/jira-social-repository) 


The Dataset was originall extracted from the Jira ITS (PostGreSQL Database) of four popular open source ecosystems i.e., the Apache Software Foundation, Spring, JBoss and CodeHaus communities.

Overview of Data
-----------------
This dataset was extracted from the Jira ITS on a PostGreSQL database and migrated to an Oracle database for simplicity and robustness reasons; which could be used for various research and practical activities. This dataset extracts tickets created on JIRA for four popular open source ecosystems (as well as the tools and infrastructure used for extraction) the Apache Software Foundation, Spring, JBoss and CodeHaus communities. The dataset hosts more than 1K projects, containing more than 700K issue reports and more than 2 million issue comments. Furthermore, comments posted by developers contain not only technical information, but also valuable information about sentiments and emotions. The full dataset (comprising the Apache projects) hosts 3516 tasks and 25306 comments by 1375 authors.

The reason why the original PostGreSQL based database had been migrated to an Oracle database is to enable to developers and the researchers to leverage the simplicity and robusrtness capabilities that an Oracle Database provides which typically is something that the PostGreSQL database lacks. This by turn furnishes the foundation to be used in conjunction with other technology components given the wider connectivity support of Oracle Databases compared to PostGreSQL databases.

To Download the Oracle database dump please use the following Google Drive link:
--------------------------------------------------------------------------------
https://drive.google.com/drive/folders/1IQpk-xkQAUaoMG52ZxP-A5FTNKURC9nO?usp=sharing

Please visit the "jira_emotion_lg" log file to get more details on the output from the Oracle Database dump operation.


To import the dump file on Oracle Database run the following "Data Pump Import" command under your oracle DB schema:

impdp system/"password"@XE dumpfile=exp_schm_jira_emotion.dmp logfile=impdp_jira_emotion.log;


Please also find the following link which can come in handy explaining how Data Pump works:
https://oracle-base.com/articles/10g/oracle-data-pump-10g
