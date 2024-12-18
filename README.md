# PROF

This repository contains the code for PROF, a modification on the OPRO algorithm as per the requirements for the E6998 project.

## Dependency requirements

The code has been verified to work under `Python 3.10.13` with the following dependencies:

```
- absl-py (2.0.0)
- google.generativeai (0.1.0)
- immutabledict (3.0.0)
- openai (0.27.2)
```

## Usage

See the PROF_demo.ipynb file for example usage on how to run the four different variants of the algorithm (OPRO, CoT, Feedback, and PROF [CoT + Feedback]).

Note that you will need to set the OPENAI_API_KEY environment variable with your OpenAI API key in order for the calls to work.