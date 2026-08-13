# 🚀 QA Engineering Portfolio

Welcome to my QA Engineering Portfolio, built around a production-grade document automation system.

I originally developed this application as a real-world, cross-platform enterprise solution using Flutter, Supabase, and Cloudflare Workers. But while building and maintaining it, something interesting happened—I realised that writing the code was only half the battle.

During the development process, I saw firsthand how seemingly tiny oversights—a forgotten UI constraint, a hardcoded file path, or an untested edge case in a dropdown—could completely break the user experience or corrupt data. I realised that a product's true value isn't just in its features, but in its reliability. "Stupid" mistakes in production can be incredibly expensive, and preventing them requires a completely different mindset than just building features. That realisation is what sparked my transition from Software Engineering into Quality Assurance.

I decided to use my own codebase as the ultimate playground to demonstrate this mindset shift. This portfolio is not just theory. It contains real, critical bugs I found, diagnosed, and fixed in a production environment. By documenting these 18 case studies, backed by actual Git commit histories and code proofs, I want to show my transition from a developer who just wanted to "make it work" into a QA Engineer who understands how to break it, secure it, and guarantee its quality.

---

## 📂 Portfolio Architecture

### 1. 🔍 In-Depth Case Studies (Code Proofs)

*This is the core of my portfolio. Real bugs, Root Cause Analyses (RCA), and actual code diffs proving the fix.*

* **[Case Study 01: Cross-Platform Path Crash](https://www.google.com/search?q=./Case_Studies/01_Windows_Path_Crash/README.md)** — Investigating a fatal `IOException` on Windows caused by hardcoded macOS file paths.
* **[Case Study 02: The Render Deadlock](https://www.google.com/search?q=./Case_Studies/02_Dialog_Freeze_Deadlock/README.md)** — Debugging a UI freeze caused by improper state lifting and infinite `setState()` loops.
* **[Case Study 03: UI Boundary Failures](https://www.google.com/search?q=./Case_Studies/03_Table_Wrapping_UI/README.md)** — Fixing table UI breakdowns when boundary conditions (extremely long strings) were met.
* **[Case Study 04: CI/CD Pipeline Stalls](https://www.google.com/search?q=./Case_Studies/04_MSIX_CI_Pipeline/README.md)** — Troubleshooting and fixing a stalled GitHub Actions workflow caused by interactive shell prompts.
* **[Case Study 05: JSON State Deserialization](https://www.google.com/search?q=./Case_Studies/05_JSON_State_Serialization/README.md)** — Ensuring backwards compatibility and preventing data loss during offline draft saves.
* **[Case Study 06: WYSIWYG PDF Image Layout Parity](https://www.google.com/search?q=./Case_Studies/06_PDF_Image_Layout_Parity/README.md)** — Fixing visual mismatch between the frontend editor and the backend PDF generator.
* **[Case Study 07: Data Integrity & Memory Uploads](https://www.google.com/search?q=./Case_Studies/07_API_Upload_and_Data_Integrity/README.md)** — Resolving upload failures by bypassing local disk I/O and fixing data mapping errors.
* **[Case Study 08: OS-Level Script Encoding](https://www.google.com/search?q=./Case_Studies/08_PowerShell_Encoding_Failure/README.md)** — Debugging an auto-updater failure caused by Unix line endings executing in a Windows PowerShell environment.
* **[Case Study 09: Draft Autosave Resilience](https://www.google.com/search?q=./Case_Studies/09_Draft_Autosave_Resilience/README.md)** — Preventing catastrophic data loss during long data-entry sessions by implementing resilient background saving.
* **[Case Study 10: CI Build Idempotency](https://www.google.com/search?q=./Case_Studies/10_CI_Build_Idempotency/README.md)** — Hardening the GitHub Actions pipeline against cached runner corruption and ephemeral file bleed.
* **[Case Study 11: UI Table Scrolling Overflow](https://www.google.com/search?q=./Case_Studies/11_UI_Table_Scrolling/README.md)** — Fixing an unconstrained UI viewport that caused scrolling elements to overflow and become inaccessible.
* **[Case Study 12: PDF Text Wrapping Engine](https://www.google.com/search?q=./Case_Studies/12_PDF_Text_Wrapping_Engine/README.md)** — Developing a custom PDF wrapping algorithm to prevent text bleeding out of document boundaries.
* **[Case Study 13: PDF Template Orientation Bounds](https://www.google.com/search?q=./Case_Studies/13_PDF_Template_Orientation/README.md)** — Resolving layout scaling issues by dynamically fetching template metadata rather than assuming static page dimensions.
* **[Case Study 14: UI Dropdown Overflow Failures](https://www.google.com/search?q=./Case_Studies/14_UI_Dropdown_Overflow/README.md)** — Preventing UI widget blowout errors when rendering dynamically loaded long-string dropdown menus.
* **[Case Study 15: Removing Heavy Dependencies](https://www.google.com/search?q=./Case_Studies/15_Removing_Heavy_Dependencies/README.md)** — Refactoring an external .NET C# dependency into native OS scripts to massively improve CI/CD stability and reduce build bloat.
* **[Case Study 16: PDF Multiline Bounding Failures](https://www.google.com/search?q=./Case_Studies/16_PDF_Multiline_Overflow/README.md)** — Hardening PDF rendering engines against word-splitting overflow when dynamically concatenating large address strings.
* **[Case Study 17: UI State & Grammar Injection](https://www.google.com/search?q=./Case_Studies/17_UI_State_Injection/README.md)** — Correcting static hardcoded strings leaking into generative artifacts, proving dynamic state injection failures.
* **[Case Study 18: Array Reordering State Logic](https://www.google.com/search?q=./Case_Studies/18_Array_Reordering_State/README.md)** — Debugging list-index out-of-bounds exceptions and state desynchronization when users manually reorder complex nested arrays.

### 2. 📋 QA Strategy & Documentation

* **[TEST_PLAN.md](https://www.google.com/search?q=./TEST_PLAN.md)** — My strategic approach to testing a massive PDF-generating client with offline capabilities.
* **[TEST_CASES.md](https://www.google.com/search?q=./TEST_CASES.md)** — A curated suite of manual functional, negative, and edge test cases.
* **[CI_CD_Analysis.md](https://www.google.com/search?q=./CI_CD_Analysis.md)** — A QA review of the GitHub Actions pipeline, proposing automated quality gates (security scans, linting).

---

## 🔒 Source Code Access

> [!NOTE]
> The full source code for this application is kept private due to licensing and proprietary reasons.
> However, if you are a recruiter or hiring manager reviewing this portfolio and would like to see the complete codebase to verify the implementations, please **send me an inquiry** and I will be happy to grant you temporary access to the full repository!
