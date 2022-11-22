FROM centos:7.4.1708
RUN yum install -y \
       java-1.8.0-openjdk  \
       java-1.8.0-openjdk-devel \
    && echo "securerandom.source=file:/dev/urandom" >> /usr/lib/jvm/java/jre/lib/security/java.security


ENV JAVA_HOME /usr/lib/jvm/java-1.8.0-openjdk-1.8.0.144-0.b01.el7_4.x86_64

CMD ["bash"]
