# Gradle Wrapper
Gradle Wrapper to create Java and Kotlin projects using Gradle as build tool. In this repo the Gradle Wrapper (gradlew commands and gradle dirctory) was extracted from other Gradle project and upgraded to latest Gradle version. This repo will maintain this whenever is necessary to upgrade.

> Note: For Linux platform replace back slash in command .\gradlew with forward slash ./gradlew command.

Clone the repo and provide proper name for the project
```console
git clone https://github.com/mmk-code/Gradle_Wrapper.git [input_project_name]
```
Move to project directory
```console
cd [input_project_name]
```
Create new Gradle Project using the following command 
```console
.\gradlew init
```
Upgrade Gradle Wrapper if required using the following command
```console
.\gradlew wrapper --gradle-version [input_version] --distribution-type bin
```
