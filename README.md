# Hotfix-Benchmark

This repository contains files and data related to the report titled **"Evaluating LLMs Performance on Hotfixes Bugs for Automatically Repair."**

## Files

- **HotfixLLMs.html**: This file contains benchmark data and experimental records related to hotfix bugs in the context of Large Language Models (LLMs). It documents the build and compile help for versions of the project with different hotfix bugs.
- **Defects4J-Hotfix**: This folder contains records of attempts to extend hotfix bugs from various projects within the Defects4J framework. The projects included are Kafka, Flink, and Codec:
  - **Codec**: The Codec project is originally included in Defects4J, and all attempts to extend hotfix bugs for this project were successful.
  - **Kafka & Flink**: These projects are not originally part of Defects4J. This folder contains records of attempts to extend hotfix bugs. However, most attempts were unsuccessful, and the folder includes detailed logs of the failed extension processes.
- **KAFKA**: This folder contains the source code and test code diff patch files for each hotfix bug in the Kafka project. It also includes the prompts used by the LLMs for each hotfix bug. 
- **FLINK**: Similar to the Kafka folder, this folder contains the source code and test code diff patch files for each hotfix bug in the Flink project. It also includes the prompts used by the LLMs for each hotfix bug. 

## Future Work

We plan to extend this benchmark by including more diverse datasets and exploring additional LLMs. Stay tuned for updates!

## Contact

For questions or feedback, feel free to reach out to the maintainers of this repository.