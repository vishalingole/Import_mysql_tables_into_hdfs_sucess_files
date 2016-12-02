# Import_mysql_tables_into_hdfs_sucess_files

For imporing tables from mysql to HDFS I have used following command:

sqoop import --connect jdbc:mysql://192.168.2.61/employees --username hadoop1 --password password --table departments --m 1
