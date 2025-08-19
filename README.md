
## Objective
Learn how to use Jenkins to build a simple Java application using Maven.

## Steps I Followed
1. Created a simple Java HelloWorld app with `HelloWorld.java`.
2. Added `pom.xml` with Maven compiler plugin.
3. Started Jenkins using Docker.
4. Configured Maven inside Jenkins (Maven 3.8.6).
5. Created a Freestyle Job in Jenkins.
6. Added Maven build step with goal `clean package`.
7. Ran the job → Got **BUILD SUCCESS**.
8. Pushed code & screenshot to this repo.

## Files
- `src/main/java/HelloWorld.java`
- `pom.xml`
- `README.md`
- `screenshot.png` (Jenkins build success)

## Output
Jenkins successfully built the project using Maven 🎉
