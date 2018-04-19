FROM mariadb:10.3.4
MAINTAINER TomoProg <helloworld0306.xxx@gmail.com>
RUN apt-get update && apt-get install -y \
	vim-tiny
ADD ./resource/my.cnf /etc/mysql/
RUN mkdir /sql_study
WORKDIR /sql_study
