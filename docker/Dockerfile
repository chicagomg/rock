FROM jenkins/ssh-agent:jdk11

RUN apt -y update && \
	apt -y upgrade

RUN apt install -y ca-certificates && \
	rm -rf /var/lib/apt/lists/*
