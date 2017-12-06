gradle-maven-template
=====================

This repository is for my personal gradle templates for private S3 maven publish.

# Usage

1. Change `group`, `ext.privateMavenBucket`, `ext.privateMavenPath` inside [`build.gradle`](./build.gradle)
2. Change `rootProject.name` inside [`settings.gradle`](./settings.gradle)
3. You can publish `./gradlew publish` to private S3 maven repository if you have a credential.

# Authentication

See. http://docs.aws.amazon.com/AWSJavaSDK/latest/javadoc/com/amazonaws/auth/DefaultAWSCredentialsProviderChain.html

