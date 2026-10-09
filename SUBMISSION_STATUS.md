# MiniProject2 submission status — October 8, 2026

This is a partial submission with seven complete project datasets and seven reviewed reflections. `bdowlin2_project_summary.csv` contains 14,828 records with the required five semicolon-separated columns. Every included project was checked against its entire WoC SHA manifest before export; partially retrieved projects are excluded rather than treated as zero activity.

Complete projects: avehtari_bda_course_aalto, eberharf_cfl, vatlab_sos, jayggg_ngstents, inqwire_sqir, tee-lab_pyddsde, and windweller_disextract.

Both notebooks include their own code. They have been executed successfully in a separate folder with only the submitted CSVs and the assignment's existing net2prj.csv, without helper modules or pre-existing retrieval caches. Install requirements.txt before running. Leave RUN_NETWORK=False to review the submitted snapshot offline. Do not start a second collector while the background retrieval process runs.

The remaining projects are OpenMS, GCAM, and OpenDA. Historical analysis for incomplete projects remains unavailable, with explicit WoCDataComplete and GapReviewComplete flags in the statistics CSV. The OpenDA manifest lists seven objects that WoC's commit store cannot return; see WOC_DATA_EXCEPTIONS.md and bdowlin2_unavailable_woc_commits.csv. GCAM still needs eleven missing records retried; OpenMS retrieval is continuing. GitHub data has not been substituted for WoC historical commit details.

Current-status classification uses September 30, 2026, as selected for this assignment: the latest GitHub default-branch commit on or before that date is Active if dated April 1, 2026 or later. Stars and forks reflect retrieval time. Monthly historical ranges use the actual returned WoC timestamps, without adding trailing zero months.

Supplementary source comparisons are in bdowlin2_source_comparison.csv. Evidence for recent themes is in bdowlin2_recent_themes.md; other evidence links appear in the project reflections.
