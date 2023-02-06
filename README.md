github-package-maven
--------------------
Testing GitHub Packages with Maven


Project Setup
-------------

Create a new GitHub **Personal Access Token (Classic)**: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

Create a new GitHub repository and clone it locally.

Create a new Maven project:
```bash
mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4
```

Move the content from the Maven project folder into the GitHub repository folder.


