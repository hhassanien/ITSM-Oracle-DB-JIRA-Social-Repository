# JIRA-Social-Repository-OracleDB
This repository is a migration by product  to Oracle DB 11g from the PostGreSQL based database jira-social-repository (https://github.com/marcoortu/jira-social-repository) 

To Download the Oracle database dump please use the following Google Drive link: https://drive.google.com/drive/folders/1IQpk-xkQAUaoMG52ZxP-A5FTNKURC9nO?usp=sharing

Please visit the "jira_emotion_lg" log file to get more details on the output from the Oracle Database dump operation.


To import the dump file on Oracle Database run the following "Data Pump Import" command under your oracle DB schema:

impdp system/"password"@XE dumpfile=exp_schm_jira_emotion.dmp logfile=impdp_jira_emotion.log;


Please also find the following link which can come in handy explaining how Data Pump works.
