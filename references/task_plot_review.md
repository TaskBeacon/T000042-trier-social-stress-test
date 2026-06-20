# Task Plot Review

## Evidence Match

- Pass: title and construct match the Trier Social Stress Test.
- Pass: rows are protocol segments, not invented task conditions.
- Pass: phase order matches README and `src/run_trial.py`: Instruction -> Baseline acclimation -> Speech preparation -> Speech delivery -> Mental arithmetic -> Recovery -> Goodbye.
- Pass: timing labels match human config: 100 ms instruction/goodbye holds, 300000 ms baseline, 600000 ms speech preparation, 300000 ms speech, 300000 ms arithmetic, 900000 ms recovery.
- Pass: response mapping shows SPACE only for start/exit screens.
- Pass: speech and arithmetic phases include neutral judges and REC cue.
- Pass: no feedback, reward, scoring, or adaptive controller is shown.

## Visual Quality

- Pass: labels and timings are readable.
- Pass: generated timeline content stays below the header band.
- Pass: fixed title and Construct subtitle are centered.
- Pass: top-right TaskBeacon logo lockup is borderless and non-overlapping.
- Pass: no generated title, logo, watermark, devices, or decorative scene is present.

## README Embed

- Pass: `README.md` contains `## 2. Task Flow`.
- Pass: the section embeds `![Task Flow](task_flow.png)`.
- Pass: final image is saved as `task_flow.png`; raw timeline is saved as `references/task_plot_timeline_raw.png`.
