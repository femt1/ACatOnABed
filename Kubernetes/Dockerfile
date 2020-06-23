FROM ubuntu:16.04
COPY jdk /jdk
COPY dacapo-9.12-MR1-bach.jar /dacapo-9.12-MR1-bach.jar
ENV JAVA_HOME /jdk
ENV PATH="${JAVA_HOME}/bin:${PATH}"

ENTRYPOINT ["java", "-verbose:gc", "-Xloggc:jdkF01verbose.txt", "-jar", "dacapo-9.12-MR1-bach.jar", "avrora", "--size=large"]
