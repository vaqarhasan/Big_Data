
File Copy Commands:
-------------------

Copy Files from HDFS to Local file system:
hadoop fs -get abc.txt /home/training/Desktop

Copy Files from Local file system to HDFS:
hadoop fs -put /home/training/Desktop/ abc.txt abc.txt

Parallel Copy:
hadoop distcp abc.txt abc1.txt

Merge Files:
hadoop fs -getmerge /user/training/shakespeare /home/training/Desktop
