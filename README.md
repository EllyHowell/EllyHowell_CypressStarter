_Repository for basic Cypress project for automation testing by Elly Howell_

## Install Node.js + Add to System Environment Variables

Download NodeJS : [NodeJs Download Page](https://nodejs.org/en/download)

System Properties > Advanced > Environment Variables > System Variables
Add variable named `NODE_HOME` to the nodejs location (i.e. _C:\Program Files\nodejs_)

## Repository Structure

By default, Cypress comes with a folder structure. The main folder is **cypress,** within which there are subfolders.

- **Fixtures:** If you are using external data inside your tests, your data can be organized inside the Fixtures folder.
- **Screenshots:** Once a run has completed (via the Run All command), the reporting will create screenshot results and add them here when a test fails. Everything under this directory is ignored by GIT to ensure no screenshot information is added to the repository.
- **Support:** The Support folder contains utilities, global commands, frequently used codes, etc. By default, this folder comes with – **commands.js**. Additional files and folders can be added as required.

## Run

### Open Cypress Dashboard

    npx cypress open

### Run All Tests

    npx cypress run

### Run Specific Test File

    npx cypress run --spec "<path_to_spec_file>"

For more commands, see: [Cypress Documentation - Commands](https://docs.cypress.io/guides/guides/command-line#Commands)
