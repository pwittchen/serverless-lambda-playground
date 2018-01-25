serverless-lambda-playground
============================
Playing around with Lambdas and Cloud Functions

requirements
------------

Please note, you need to create your [AWS](https://aws.amazon.com) account first and then install and configure [Serverless](http://serverless.com) framework. Moreover, each Lambda Function needs to have API GateWay attached in order to be accessible in the public.

deployment
----------

go to the one of the project directories and type:

```
sls deploy
```

building JVM projects
---------------------

In the case of the Java project, we need to build it first as follows:

```
./gradlew build
```

In the case of Kotlin project, we should build it with:

```
./gradlew shadowJar
```

If we're missing Gradle Wrapper, but we have Gradle installed in the system, we can go to the project directory and just type:

```
gradle wrapper
```
