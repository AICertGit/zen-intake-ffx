# ZenIntake 1:40 Demo Video Script (100 seconds)

Target app URL:
- https://zenintake-web-poc.azurewebsites.net/

Recording target:
- 1 minute 40 seconds total
- Single take

## Timeline + exact narration

### 0:00 - 0:08
Narration:
"Fairfax NCS intake can be slow and manual, which creates delays, duplicate records, and fraud risk."

Action:
- Show the form top section.

### 0:08 - 0:18
Narration:
"ZenIntake is applicant-first. Residents enter information once, and the backend pre-screen runs automatically."

Action:
- Slowly move cursor over form fields.

### 0:18 - 0:32
Narration:
"The applicant enters name, address, employer, income, household size, and child-care need."

Action:
- Briefly click each field (leave sample values).

### 0:32 - 0:40
Narration:
"Now I submit the application and trigger the full workflow."

Action:
- Click **Submit Application and Run Pre-Screen**.

### 0:40 - 0:56
Narration:
"First, we run fuzzy identity matching against an MCI-style data lake to link to an existing golden record and prevent duplicate profiles."

Action:
- Point at match confidence + MCI ID metrics.

### 0:56 - 1:10
Narration:
"Second, we verify the employer with Crustdata for anti-fraud checks, with resilient fallback to keep operations stable."

Action:
- Point at verification status, trust score, source.

### 1:10 - 1:24
Narration:
"Third, transparent policy rules evaluate residency, child-care need, income threshold, identity confidence, and duplicate conflict."

Action:
- Scroll to rules checklist table.

### 1:24 - 1:36
Narration:
"The system outputs AUTO_APPROVE, MANUAL_REVIEW, or NOT_ELIGIBLE, so caseworkers focus on exceptions instead of data entry."

Action:
- Hold cursor on final decision area.

### 1:36 - 1:40
Narration:
"Result: faster intake, stronger fraud controls, and auditable, explainable case routing for Fairfax NCS."

Action:
- Hold still and stop recording.

## Fast recording setup (Windows)

### Option A: Xbox Game Bar
1. Press `Win + G`
2. Open Capture panel
3. Press `Win + Alt + R` to start
4. Run the timeline above
5. Press `Win + Alt + R` to stop
6. Video saved under `Videos/Captures`

### Option B: Loom
1. Select Screen + Cam (small bubble)
2. 1080p, mic on
3. Start recording
4. Follow timeline exactly
5. Trim first 2-3 seconds

## Backup line if API is slow
"External verification includes safe fallback behavior, so the workflow still returns a pre-screen outcome for operations continuity."
