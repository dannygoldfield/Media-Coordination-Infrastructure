# Sequenced Build Plan

Derived from *Media Workflow System Design + Build Plan v2*.  
Keep this short and practical for sprint tracking.

---

## Phase 1 — Foundations (~10 h)
- Repo created: README and .gitignore in place.
- Folder skeleton set. Sample project template.
- Bridge Downloader preset and IPTC template exported.
- Lightroom Classic: write XMP enabled. Test import from `Photos_RAW`.
- Premiere: Same-as-Project scratch. Proxy preset chosen and attached.

---

## Phase 2 — Automation / Scripts (~12 h)
- `make_proxies.py` and `to_shorts.py` working on sample footage.
- `burn_captions.py` handles standard SRT.
- `verify_and_rsync.sh` copies SSD → Konstantine with checksums.
- Media Encoder watch folders: `_To_Social`, `_To_Master`, `_To_Thumbs`.

---

## Phase 3 — WordPress Publish (~14 h)
- CPT `loop` created with ACF fields.
- REST token auth verified from local script.
- Script creates post with video URL, thumb, transcript.
- Divi template renders Loop pages. Grid shows latest.

---

## Phase 4 — RAG Index (deferred, ~16 h)
- Collect metadata: LRC XMP, Bridge XMP, CSV exports, Drive lists, repo text.
- Local SQLite + embeddings. CLI query. YAML toggle.

---

## Phase 5 — Test and Refine (~9 h)
- Run mixed ingest → proxy edit → vertical export → publish to YouTube + WP.
- Measure time end-to-end.
- Fix relinks. Verify archive rsync.
- Write learnings back into docs.

---

## Add-ons
- Capture scripts for Numbers and WebAR (~8 h).
- Repos + WP tagging for project filtering (~4 h).

---

## Definition of Done
- New shoot goes from ingest → YouTube → WordPress using this system.
- No relinks after moving to Konstantine.
- Steps documented in this repo.
