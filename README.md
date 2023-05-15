# Software Evolution and Maintenance project

## Team members

- Ahmed Wael Nagy Wanas - 20206008
- Adham Hazem Fahmy Shafei - 20206011
- Omar Adel Abdel Hamid Ahmed Brikaa - 20206043
- Ali Esmat Ahmed Orfy - 20206123

## GitHub repository

https://github.com/seam-project/seam-project

## Cloning the repository

This repo consists of multiple git submodules.
Make sure to clone the submodules as well using the `--recurse-submodules` flag

```bash
git clone --recurse-submodules git@github.com:seam-project/seam-project.git
```

## Viewing the SonarQube reports

Check the [sonarqube-reports](./sonarqube-reports/) directory.
The PDF files are a general overview of the code and the JSON files are the first 10000 code quality issues
(20 JSON files x 500 issues each).

[The `before-changes` directory](./sonarqube-reports/before-changes/) contains the static analysis reports
before implementing the proposed changes.
[The `after-changes` directory](./sonarqube-reports/after-changes/) contains the static analysis reports
of the added code.

Some new code smells originated for the following reasons:

- The need to stay consistent with already existing code (for example using PascalCase in enum constants)
- Merging code from UniTime master

## Viewing the project description

Check the [project-description](./project-description/) directory.

## Viewing the suggested changes descriptions and ticketing system

Check the [changes-description](./changes-description/) directory.
Ticketing is done on [ClickUp](https://sharing.clickup.com/9009133533/l/h/8cfrxyx-300/e42d30a50b342ea).
Github integration is hidden from the public ClickUp view. Contact us if you would like to see it.
We chose to implement the feature that allows an admin to list all of the students and
their registered courses information.

## Viewing the class diagrams

Check [`models.pdf` in the `models` directory](./models/models.pdf)

## Building and running the application

Follow the instructions in [unitime-docker](https://github.com/seam-project/unitime-docker).

## Generating SonarQube reports

Follow the instructions in [sonarqube-compose](https://github.com/seam-project/sonarqube-compose).
