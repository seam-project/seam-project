# Software Evolution and Maintenance project

## Team members

- Ahmed Wael Nagy Wanas - 20206008
- Adham Hazem Fahmy Shafei - 20206011
- Omar Adel Abdel Hamid Ahmed Brikaa - 20206043
- Ali Esmat Ahmed Orfy - 20206123

## GitHub repository

https://github.com/seam-project/seam-project

## Cloning the repo

This repo consists of multiple git submodules.
Make sure to clone the submodules as well using the `--recurse-submodules` flag

```bash
git clone --recurse-submodules git@github.com:seam-project/seam-project.git
```

## Viewing the SonarQube reports

Check the [sonarqube-reports](./sonarqube-reports) directory.
The PDF files are a general overview of the code and the JSON files are the first 10000 code quality issues
(20 JSON files x 500 issues each).

## Building and running the application

Follow the instructions in [unitime-docker](https://github.com/seam-project/unitime-docker).

## Generating SonarQube reports

Follow the instructions in [sonarqube-compose](https://github.com/seam-project/sonarqube-compose).
