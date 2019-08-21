FROM flink:1.8.1-scala_2.12

ARG hadoop_jar
ARG job_jar

COPY --chown=flink:flink $hadoop_jar $job_jar $FLINK_HOME/lib/

USER flink
