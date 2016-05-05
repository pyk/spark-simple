# Spark Simple

A simple spark application.

## Build and Submit

    sbt package
    spark-submit --class "SimpleApp" --master local[4] target/scala-2.10/simple-project_2.10-1.0.jar
