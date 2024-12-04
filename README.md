# Commit-Types
The following Commit Types are permissible:


feat: A code change that introduces new functionality in the main program (feature)

fix: A bug fix in the source code or any of the artifact scripts (e.g. fix in the pom.xml) but not correction of spelling mistakes.

refactor: A code change that neither fixes a bug nor adds a feature and therefore does not change any behavior of the program or the project artifacts

test: Adding missing tests, correcting existing tests or adding test resource files

docs: Documentation only changes. This may be source code documentation (e.g. JavaDoc), the README or other artifacts that contain documentation.

style: Changes only regarding the style of resource files (e.g. removing blank lines).

ci: Changes to CI/CD configuration files (e.g. .gitlab-ci.yml, .docker etc)

config: Changes to properties/config files (.config/.properties etc) that belong to the application

build: Changes that affect the build system or external dependencies (example scopes: maven, gulp, broccoli, npm)

perf: A code change that improves performance

core: Additions of or changes on files that cannot be allocated to one of the other categories but are part of the system. This includes for example files for the build system (e.g. pom.xml) or the version control system (e.g. .gitignore)

tmp: This type marks commits that only should exist temporary in the system and the only reason to commit these to the Git server is for testing purposes. They are not allowed to be committed to the master or production branch ever! Specifying test commits with this types may help to avoid adding them to a release by accident.

revert: Revert something
