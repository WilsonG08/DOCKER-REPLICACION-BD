![image](https://github.com/WilsonG08/DOCKER-REPLICACION-BD/assets/117754219/6979cbfc-14a1-4a1e-b757-7bf3fbf13f7f)


-------

CHANGE MASTER TO MASTER_HOST='mysql_master', MASTER_USER='root',
MASTER_PASSWORD='root1';
CHANGE MASTER TO MASTER_LOG_FILE='mysql-bin.00001',MASTER_LOG_POS=487;
START SLAVE;



-----------


