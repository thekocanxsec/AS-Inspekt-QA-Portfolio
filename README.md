# 🚀 QA Engineering Portfolio: AS Inspekt

Welcome to my **QA Engineering Portfolio**, built around the `AS Inspekt` repository. 

Originally, developed this for a real-world, cross-platform application (Windows, macOS, iOS) using **Flutter, Supabase, and Cloudflare Workers**. However, as my career focus shifted towards **Quality Assurance and Software Testing**, I realized that my own codebase is the perfect playground to demonstrate how I approach software quality.

This portfolio is not just theory. It contains **some of the most critical bugs I found, diagnosed, and fixed**, backed up by actual Git commit histories and code proofs. It demonstrates my transition from "just making it work" to "engineering for resilience, scalability, and quality."

---

## 📂 Portfolio Architecture

### 1. 🔍 In-Depth Case Studies (Code Proofs)
*This is the core of my portfolio. Real bugs, Root Cause Analyses (RCA), and actual code diffs proving the fix.*
*   **[Case Study 01: Cross-Platform Path Crash](./Case_Studies/01_Windows_Path_Crash/README.md)** — Investigating a fatal `IOException` on Windows caused by hardcoded macOS file paths.
*   **[Case Study 02: The Render Deadlock](./Case_Studies/02_Dialog_Freeze_Deadlock/README.md)** — Debugging a UI freeze caused by improper state lifting and infinite `setState()` loops.
*   **[Case Study 03: UI Boundary Failures](./Case_Studies/03_Table_Wrapping_UI/README.md)** — Fixing table UI breakdowns when boundary conditions (extremely long strings) were met.
*   **[Case Study 04: CI/CD Pipeline Stalls](./Case_Studies/04_MSIX_CI_Pipeline/README.md)** — Troubleshooting and fixing a stalled GitHub Actions workflow caused by interactive shell prompts.
*   **[Case Study 05: JSON State Deserialization](./Case_Studies/05_JSON_State_Serialization/README.md)** — Ensuring backwards compatibility and preventing data loss during offline draft saves.
*   **[Case Study 06: WYSIWYG PDF Image Layout Parity](./Case_Studies/06_PDF_Image_Layout_Parity/README.md)** — Fixing visual mismatch between the frontend editor and the backend PDF generator.
*   **[Case Study 07: Data Integrity & Memory Uploads](./Case_Studies/07_API_Upload_and_Data_Integrity/README.md)** — Resolving upload failures by bypassing local disk I/O and fixing data mapping errors.
*   **[Case Study 08: OS-Level Script Encoding](./Case_Studies/08_PowerShell_Encoding_Failure/README.md)** — Debugging an auto-updater failure caused by Unix line endings executing in a Windows PowerShell environment.
*   **[Case Study 09: Draft Autosave Resilience](./Case_Studies/09_Draft_Autosave_Resilience/README.md)** — Preventing catastrophic data loss during long data-entry sessions by implementing resilient background saving.
*   **[Case Study 10: CI Build Idempotency](./Case_Studies/10_CI_Build_Idempotency/README.md)** — Hardening the GitHub Actions pipeline against cached runner corruption and ephemeral file bleed.

### 2. 📋 QA Strategy & Documentation
*   **[TEST_PLAN.md](./TEST_PLAN.md)** — My strategic approach to testing a massive PDF-generating client with offline capabilities.
*   **[TEST_CASES.md](./TEST_CASES.md)** — A curated suite of manual functional, negative, and edge test cases.
*   **[CI_CD_Analysis.md](./CI_CD_Analysis.md)** — A QA review of the GitHub Actions pipeline, proposing automated quality gates (security scans, linting).

---

## 🔒 Source Code Access
> [!NOTE]  
> The full source code for this application is kept private due to licensing and proprietary reasons. 
> 
> However, if you are a recruiter or hiring manager reviewing this portfolio and would like to see the complete codebase to verify the implementations, please **send me an inquiry** and I will be happy to grant you temporary access to the full repository!
