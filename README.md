[ru](./README_RU.md)

# kvrep

1. Replacer - a utility for key replacement in a file structure, recursively replaces keys with values in text files within a hierarchical file structure.
    1. Supports JSON and YAML formats for storing keys and values.
    0. Optionally copies the original content to a specified destination directory before performing the replacement.

# Processing Stages

1. repl performs the following processing stages:
   1. Key Collection: Loading and merging keys from JSON and YAML files.
   2. Key Replacement: Recursively replacing all keys in files with values, which may contain nested keys.
   3. File Copying: Optionally copies content from the source path to the target directory before performing the replacement.

# Example Command

1. The command to run the script is as follows:

```./kvrep --path=source_dir --keys=keys.json keys.yaml --dest=destination_dir```

2. In this example:
   1. `source_dir` — the source directory with files.
   0. `keys.json`, `keys.yaml` — files with keys and values.
   0. `destination_dir` — the target directory for copying content before key replacement.

# Absence of Analogues in Standard Tools

1. According to OpenAI: Standard Python tools and other programming languages do not provide functionality for recursive key replacement in arbitrary text files with support for dynamic values and nested keys in one solution. This utility combines these capabilities in one script.

# Areas of Application

1. Processing configuration files.
0. Key replacement in templates and documentation.
0. Automation of configuration and deployment tasks.

# Contributors

1. Coding - ChatGPT version 2.0, AI from OpenAI, specializing in programming assistance and solving technical problems.
2. Specification, debugging, and publication - Still Swamp.

# Publisher's Notes

1. This project is a joke, and as is well known, there's a grain of truth in every joke.
0. The script was developed by OpenAI based on the [specification](./task.ai).
0. The working version required approximately 10 iterations, including fixing specification and script errors.
0. I had not previously worked with Python, but the task was simple enough for debugging.

# Links

1. [Base Specification](./task.ai)
