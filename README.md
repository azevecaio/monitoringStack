# Monitoring Stack
This is a monitoring stack to build zabbix + grafana + postgres

## Requirements
docker/docker-compose

## Steps to run
1. Clone the repository
2. Define root variable path in .env file named "dir" to root folder application
3. Go to root dir
4. docker-compose up -d
5. docker-compose ps

*IMPORTANT NOTE: WHEN YOU PUSH OR UPDATE THIS REPOSITORY PAY CLOSE ATTENTION TO GIT CONFIG "git config --list | grep crlf" BECAUSE THIS CAN CAUSE SOME ISSUES IN ENDLINE BEETWHEN LINUX AND WINDOWS ENVIROMENT. THE PARAMETER MUST BE core.autocrlf=input