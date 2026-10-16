AML Mod Development Documents — Organized Collection
====================================================

Deduplicated collection of instruction / reference documents
for GTA:SA Android AML mod development (CLEO → native).

File overview
-------------
00_README.txt                          — this file

01_Core_Rules_and_Protocols.txt        — Authoritative rules
   • CONSOLIDATED PROTOCOL v1.1
   • CANONICAL FIXES & ERRATA
   • MASTER PROMPT V1.0
   • Correction Acknowledged (INI header)

02_Conversion_Templates_and_Patterns.txt
   • AML CSA AUTOMATIC PATTERN
   • AML CSA / CSI → AML CONVERSION (teaching)
   • Cleo convert resource
   • CSI menu create
   • CSI button pause menu option

03_Lessons_Session_Diary_and_Analysis.txt
   • Session Diary & Handbook
   • Lessons Learned & Fixes
   • Deep Analysis stub (full memo removed — it duplicated 01/02/04)

04_Reference_Data_IDs_and_Enums.txt
   • ENUMS
   • PEDS IDS
   • VEHICLE VARIATIONS
   • WEAPON IDS
   • STATISTICS ID

05_Opcode_References.txt               — DEDUPLICATED
   • PC 2.00 opcodes (canonical full list, internal dups collapsed)
   • PC classic — only the 1 ID not in PC 2.00
   • PS2-only — 36 opcodes not present in PC 2.00
   (Full PC classic + full PS2 lists removed as near-subsets)

Deduplication notes (this pass)
-------------------------------
• Opcode file cut ~57%: PC ≈ subset of PC 2.00; PS2 kept only unique IDs.
• Deep Analysis section removed from 03 (~61% smaller): it restated
  protocols, templates, and ID tables already in 01/02/04.
• Template/code snippets that repeat across protocol sections were left
  in place so each document remains usable on its own.

Authority order (when docs disagree)
------------------------------------
1. universal rule v2.6 (if present)
2. CANONICAL FIXES & ERRATA
3. CONSOLIDATED PROTOCOL v1.1
4. MASTER PROMPT V1.0
5. Pattern / template docs
6. Reference data / opcodes

