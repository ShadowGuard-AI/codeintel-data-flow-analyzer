![A star party with no lettering: the mesa edge in flat stone, a chart corner lifting beneath its pinning stone, telescopes tipped toward dark, hooded torches glowing dim red between them, a folding table with charts and stones, cold coffee beside a chart, desert dropping away dark, thin cloud high at the horizon, and a sky thick with stars](intro-banner.png)

# codeintel-Data-Flow-Analyzer

![An hour past sunset on the mesa: telescopes in a loose row each pointing at a different star, sky grading from desert dusk orange at the horizon into stratosphere blue, charts weighted with stones on a folding table and on the ground, hooded red torches dim along the path, cold coffee beside a chart, thin high cloud at the far edge, and codeintel-data-flow-analyzer chalked by hand on the side of the table](banner.png)

![One telescope in side view at dusk: a plain tube tilted up shallow on a tripod on flat mesa stone, desert dusk orange on the high rim, one star chart under the tripod pinned at one corner by a single stone, a small red capped lens cover hanging from the mount, and codeintel-data-flow-analyzer lettered below as a forecast entry](logo.png)

![The mesa top in three depths: stars steady while thin cloud layers cross high and slow, chart corners lifting under their weighting stones in the night breeze with hooded red torches flickering at the hood edge and one telescope tube easing through a small arc to a new star, and cold coffee in its flask forming a faint skin once over a long interval](scene.svg)


Lists every line in a Python source file that mentions a sensitive keyword, and runs bandit on the file. - Focused on Tools for static code analysis, vulnerability scanning, and code quality assurance

Matches are unfiltered substring hits, comments included. The tool does not trace data flow and does not identify leaks or injection points. Matched lines are written into the local report in full, so a real secret on a matched line will appear in the report file in full. The report section for these matches is named keyword_lines. If bandit is missing or its output cannot be parsed, the run exits 1 and the JSON report records a bandit_status field naming the failure.

> **Night log margin note: matched lines are written in full.** Matched lines go into the local report in full, under the report section named keyword_lines. A real secret sitting on a matched line will appear in the report file in full.

> **Night log margin note: keyword lines, not data flow.** Matches are unfiltered substring hits, comments included. The tool does not trace data flow and does not identify leaks or injection points.

![Major separator: a barometer needle trembling toward storm and back across the full rule, panel grey on stratosphere blue](sep-heavy.svg)

## Install
`git clone https://github.com/ShadowStrikeHQ/codeintel-data-flow-analyzer`

> **Night log margin note: clone line flagged.** The install line above points to ShadowStrikeHQ, not to ShadowGuard-AI. It is preserved as printed and flagged here, not quietly corrected.

![Minor separator: one centred barometer needle tremble with plain rule on either side, panel grey on stratosphere blue](sep-light.svg)

## Usage
`./codeintel-data-flow-analyzer [params]`

> **Night log margin note: usage line flagged.** The usage line above is a placeholder. The parser in main.py requires --source_file and --sensitive_data, and offers --output_file, --log_file, --bandit_severity_threshold, and --bandit_confidence_threshold.

![Major separator: a barometer needle trembling toward storm and back across the full rule, panel grey on stratosphere blue](sep-heavy.svg)

## Parameters
- `-h`: Show help message and exit
- `--source_file`: Path to the Python source file to analyze.
- `--sensitive_data`: No description provided
- `--output_file`: Optional file to write the analysis results to.
- `--log_file`: Optional file to save logs to.
- `--bandit_severity_threshold`: No description provided
- `--bandit_confidence_threshold`: No description provided

![Major separator: a barometer needle trembling toward storm and back across the full rule, panel grey on stratosphere blue](sep-heavy.svg)

## License
Copyright (c) ShadowStrikeHQ

> **Night log margin note: copyright line flagged.** The closing line above reads Copyright (c) ShadowStrikeHQ, preserved as printed. The repository LICENSE file carries the MIT License.
