# Jenkins Demo Pipeline

This is a simple repository for demonstrating Jenkins Git integration using:

- Scripted pipeline
- Declarative Jenkinsfile pipeline

## Structure

- `Jenkinsfile`: Defines a simple CI pipeline
- `build.sh`: Simulates a build step
- `test.sh`: Simulates a test step
- `src/`: Contains dummy source content

## How to Use

1. Fork or clone this repo into your GitHub.
2. Create Jenkins pipeline jobs:
   - One using "Pipeline script"
   - One using "Pipeline script from SCM" (Declarative Jenkinsfile)
3. Trigger builds and observe the CI process.
