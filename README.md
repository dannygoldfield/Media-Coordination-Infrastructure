# Media Coordination Infrastructure

**Keeper of truth** for workflow docs, templates, and automation.

- GitHub stores docs, checklists, and scripts.
- Large media stays off Git on external drives and cloud.
- We keep indexes and metadata that point to media locations.

## Layout
Workflow-Docs/          Process docs in Markdown  
Templates/              Naming, checklists, Bridge templates  
Scripts/                Automation (Python, Node, Bash)  
Archive-Indexes/        Pointers to media on Konstantine, SSD, Google Drive  

## Commit rules
- Do not commit RAWs, Adobe project files, or video. See `.gitignore`.
- Small diagrams are OK if needed for docs.
- Write concise commit messages that describe intent.

## Next
- Add Workflow-Docs/Media-Workflow-System-Design.md  
- Add Workflow-Docs/Sequenced-Build-Plan.md  
- Add Archive-Indexes/Konstantine-Drive.md with canonical paths
