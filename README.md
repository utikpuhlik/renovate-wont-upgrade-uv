# Renovate won't upgrade dependencies in pyproject.toml and uv.lock with UV or PEP-621 manager #34181

## Current behavior
For 12.02.2025 the boto3 package has latest version **1.36.17**, in my pyproject.toml and uv.lock **1.36.13** is specified. In logs down bellow renovate successfully detect package and its version "packageName":"boto3". However, the created MR contains only CI/CD and python-version related things
![image](https://github.com/user-attachments/assets/523f936e-08aa-4798-8092-c02b9f258766)


## Expected behavior
The boto3 package or whatever package defined in my pyproject.toml list should be upgraded to the next minor version.

## Link to the Renovate issue or Discussion
https://github.com/renovatebot/renovate/discussions/34181

