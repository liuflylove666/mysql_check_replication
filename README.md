# mysql_check_replication
#运行环境python3.6+
################
python test_v1.py -f test.cnf
################
#crontab -l
5 5 * * 7 . /data/py3venv/bin/activate && python /data/soft/scripts/mysql_checksum/test_v1.py  -f test.cnf
