# Pipelines

A repo containing the various pipelines I want created in my concourse server.

## Format

{
  "name": "<pipeline name>",
  "pipeline_def": "<url that points to your pipeline definition file>",
  "vars_file": ["<zero or more urls that point to the variables files you'll need to use>","<if multiple files are listed they'll be applied in the same order you input them here with the later files overriding any earlier files with overlapping variables>"]
}