# JIRA-Social-Repository-OracleDB
This repository is a migration by product  to Oracle DB 11g from the PostGreSQL based database jira-social-repository (https://github.com/marcoortu/jira-social-repository) 

To Download the Oracle database dump please use the following link: https://drive.google.com/drive/folders/1IQpk-xkQAUaoMG52ZxP-A5FTNKURC9nO?usp=sharing

The following is the log output from the Oracle Database dump operation:
-----------------------------------------------------------------------------------------------------------------------
Export: Release 11.2.0.2.0 - Production on Sat Jul 18 13:38:30 2020

Copyright (c) 1982, 2009, Oracle and/or its affiliates.  All rights reserved.
;;; 
Connected to: Oracle Database 11g Express Edition Release 11.2.0.2.0 - 64bit Production
Starting "SYSTEM"."SYS_EXPORT_SCHEMA_01":  system/********@XE DUMPFILE=exp_schm_jira_emotion.dmp LOGFILE=jira_emotion_lg.log SCHEMAS=jira_emotion 
Estimate in progress using BLOCKS method...
Processing object type SCHEMA_EXPORT/TABLE/TABLE_DATA
Total estimation using BLOCKS method: 5.144 GB
Processing object type SCHEMA_EXPORT/USER
Processing object type SCHEMA_EXPORT/SYSTEM_GRANT
Processing object type SCHEMA_EXPORT/ROLE_GRANT
Processing object type SCHEMA_EXPORT/DEFAULT_ROLE
Processing object type SCHEMA_EXPORT/PRE_SCHEMA/PROCACT_SCHEMA
Processing object type SCHEMA_EXPORT/TABLE/TABLE
Processing object type SCHEMA_EXPORT/TABLE/STATISTICS/TABLE_STATISTICS
. . exported "JIRA_EMOTION"."ORA_JIRA_ISSUE_COMMENT"     1.367 GB 2087290 rows
. . exported "JIRA_EMOTION"."ORA_JIRA_ISSUE_REPORT"      1.070 GB  701002 rows
. . exported "JIRA_EMOTION"."ORA_JIRA_ISSUE_CHANGELOG_ITEM"  729.7 MB 4831144 rows
. . exported "JIRA_EMOTION"."ORA_JIRA_ISSUE_BOT_COMMENT"  292.2 MB  239232 rows
. . exported "JIRA_EMOTION"."ORA_JIRA_ISSUE_ATTACHMENT"  48.07 MB   59833 rows
. . exported "JIRA_EMOTION"."ORA_JIRA_USER"              19.56 MB  103184 rows
. . exported "JIRA_EMOTION"."ORA_JIRA_ISSUE_SUB_TASK"    10.05 MB   38880 rows
. . exported "JIRA_EMOTION"."ORA_JIRA_ISSUE_AFFECTEDVERSION"  6.284 MB  505958 rows
. . exported "JIRA_EMOTION"."ORA_JIRA_ISSUE_FIXVERSION"  6.359 MB  511408 rows
. . exported "JIRA_EMOTION"."ORA_JIRA_VERSION"           2.373 MB   10793 rows
. . exported "JIRA_EMOTION"."ORA_PROJECT_DAILY_STATISTICS"  2.121 MB   49008 rows
Master table "SYSTEM"."SYS_EXPORT_SCHEMA_01" successfully loaded/unloaded
******************************************************************************
Dump file set for SYSTEM.SYS_EXPORT_SCHEMA_01 is:
  /u01/app/oracle/admin/XE/dpdump/exp_schm_jira_emotion.dmp
Job "SYSTEM"."SYS_EXPORT_SCHEMA_01" successfully completed at 14:10:21
-----------------------------------------------------------------------------------------------------------------------
