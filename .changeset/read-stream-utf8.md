---
"@kilocode/cli": patch
---

Restore streaming reads for UTF-8 files in the `read` tool so large logs and artifacts no longer get fully buffered into memory.
