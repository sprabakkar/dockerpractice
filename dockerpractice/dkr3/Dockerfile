FROM ubuntu:16.04
RUN apt-get update && apt-get install -y \
	curl \
	vim \
	openjdk-8-jdk
ENTRYPOINT ["ping", "-c", "50"]
CMD ["127.0.0.1"]
