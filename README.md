![Banner](banner.png)

# codeintel-Data-Flow-Analyzer
Lists every line in a Python source file that mentions a sensitive keyword, and runs bandit on the file. - Focused on Tools for static code analysis, vulnerability scanning, and code quality assurance

Matches are unfiltered substring hits, comments included. The tool does not trace data flow and does not identify leaks or injection points. Matched lines are written into the local report in full, so a real secret on a matched line will appear in the report file in full. The report section for these matches is named keyword_lines. If bandit is missing or its output cannot be parsed, the run exits 1 and the JSON report records a bandit_status field naming the failure.

## Install
`git clone https://github.com/ShadowStrikeHQ/codeintel-data-flow-analyzer`

## Usage
`./codeintel-data-flow-analyzer [params]`

## Parameters
- `-h`: Show help message and exit
- `--source_file`: Path to the Python source file to analyze.
- `--sensitive_data`: No description provided
- `--output_file`: Optional file to write the analysis results to.
- `--log_file`: Optional file to save logs to.
- `--bandit_severity_threshold`: No description provided
- `--bandit_confidence_threshold`: No description provided

## License
Copyright (c) ShadowStrikeHQ
