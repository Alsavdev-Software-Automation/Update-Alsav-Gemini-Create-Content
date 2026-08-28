# Change Log

## Stable Builds

<details open>
<summary><strong>2.6.3 — 2026-08-28</strong></summary>

* **CAPTCHA:** Added 3× automatic retry, improved Buster accuracy, and seamless 2Captcha API fallback.
* **Media Processing:** Added Base64 and DOCX image upload for Featured Image (FIFU); improved first-image removal.
* **Excel Reports:** Fixed Post ID mapping and adjusted columns for Word Files mode.
* **Verification:** Enhanced article content verification with HTML entity and smart quote normalization.
* **General:** UI and performance optimizations.

</details>

<details>
<summary><strong>2.6.2 — 2026-08-22</strong></summary>

* **PublishContent:** Added Word Files support and fixed related bugs.
* **GrabContent:** Added Word Files support.

</details>

<details>
<summary><strong>2.6.1 — 2026-08-21</strong></summary>

* Strict domain verification for published posts.
* Improved Word Files source matching by filename.
* Rolled back CAPTCHA solver.

</details>

<details>
<summary><strong>2.6.0 — 2026-08-20</strong></summary>

* Fixed CAPTCHA solver issues.

</details>

<details>
<summary><strong>2.5.8 — 2026-08-10</strong></summary>

* Added CAPTCHA solver after navigating to WP Admin.
* Adjusted UI and export filenames.

</details>

<details>
<summary><strong>2.5.7 — 2026-08-06</strong></summary>

* Fixed Task Concept in GenerateContentOnly.
* Updated language and target country from Portugal.

</details>

<details>
<summary><strong>2.5.6 — 2026-07-25</strong></summary>

* Added Task Concept for GenerateContentOnly (Beta).
* Added GetImage feature to GenerateContentOnly with automatic document insertion.

</details>

<details>
<summary><strong>2.5.5 — 2026-07-02</strong></summary>

* Removed API keys when their usage limit is reached.
* Fixed missing report files in GenerateContentOnly.

</details>

<details>
<summary><strong>2.5.4 — 2026-06-29</strong></summary>

* Randomized API key selection across all features.
* Improved API key distribution.

</details>

<details>
<summary><strong>2.5.3 — 2026-05-19</strong></summary>

* Enhanced error logging and post verification in WordPressService.

</details>

<details>
<summary><strong>2.5.2 — 2026-05-18</strong></summary>

* Fixed source-link object mismatch in reports.

</details>

<details>
<summary><strong>2.5.1 — 2026-05-15</strong></summary>

* Improved post verification using cache.

</details>

<details>
<summary><strong>2.5.0 — 2026-05-14</strong></summary>

* Improved error-page handling.

</details>

<details>
<summary><strong>2.4.9 — 2026-05-09</strong></summary>

* Added content verification for GenerateContentOnly.

</details>

<details>
<summary><strong>2.4.8 — 2026-04-29</strong></summary>

* Integrated 2Captcha and VPN support.

</details>

<details>
<summary><strong>2.4.7 — 2026-04-23</strong></summary>

* Improved GrabContent title extraction.
* Removed content noise in PublishContent.

</details>

<details>
<summary><strong>2.4.6 — 2026-04-16</strong></summary>

* Improved logging and API key usage in GenerateContentOnly.
* Enhanced link injection in DOCX Adapter.
* Refined CAPTCHA handling in solveCaptcha.

</details>

<details>
<summary><strong>2.4.5 — 2026-04-10</strong></summary>

* Added built-in CAPTCHA solver.
* Enhanced error handling during content generation.

</details>

<details>
<summary><strong>2.4.4 — 2026-04-04</strong></summary>

* Updated GrabContent title extraction.

</details>

<details>
<summary><strong>2.4.3 — 2026-03-17</strong></summary>

* Adjusted timeout for failed-login detection.
* Improved content-setting logic.
* Fixed login environment handling, including critical checks and confirmation emails.

</details>

<details>
<summary><strong>2.4.1 — 2026-03-14</strong></summary>

* Added scheduling with date ranges.
* Fixed automatic sorting in result exports.
* Added batch retries for final attempts.

</details>

<details>
<summary><strong>2.3.9 — 2026-03-03</strong></summary>

* Added retries to the login flow.
* Added anticipation handling for draft posts.

</details>

<details>
<summary><strong>2.3.8 — 2026-02-24</strong></summary>

* Improved log information.

</details>

<details>
<summary><strong>2.3.7 — 2026-02-23</strong></summary>

* Fixed file-extension path bugs.
* Enhanced post-content verification and error handling.

</details>

<details>
<summary><strong>2.3.6 — 2026-02-20</strong></summary>

* Improved category-selection logic.
* Refactored publishing methods.
* Improved content-existence verification and hyperlink retrieval.

</details>

<details>
<summary><strong>2.3.5 — 2026-02-18</strong></summary>

* Added confirmation-email checking after login.
* Improved login navigation.

</details>

<details>
<summary><strong>2.3.3 — 2026-02-18</strong></summary>

* Added an option to navigate to a new post.

</details>

<details>
<summary><strong>2.3.2 — 2026-02-17</strong></summary>

* Added two image-host options to GrabContent.
* Improved critical checks in PublishContent.

</details>

<details>
<summary><strong>2.3.0 — 2026-02-17</strong></summary>

* Improved metadata extraction from anchors.

</details>

<details>
<summary><strong>2.2.9 — 2026-02-13</strong></summary>

* Added CyberGhost VPN option.

</details>

<details>
<summary><strong>2.2.8 — 2026-02-13</strong></summary>

* Added GrabContent by document link.
* Refactored PublishContent.
* Updated PublishContent schema.

</details>

<details>
<summary><strong>2.2.4 — 2026-02-08</strong></summary>

* Fixed SEO Plugin handling.
* Added SEO Plugin Checker.
* Fixed fatal-error handling.

</details>

<details>
<summary><strong>2.2.3 — 2026-02-08</strong></summary>

* Fixed Yoast feature.
* Added Publish by Document Link.
* Fixed Generate Only feature.

</details>

<details>
<summary><strong>2.2.2 — 2026-01-24</strong></summary>

* Separated SEO Plugin functionality.
* Added Yoast feature.

</details>

<details>
<summary><strong>2.2.1 — 2026-01-21</strong></summary>

* Prevented unwanted Aiseso page opening.

</details>

<details>
<summary><strong>2.2.0 — 2026-01-12</strong></summary>

* Updated Unsplash selector.

</details>

<details>
<summary><strong>2.1.9 — 2025-12-08</strong></summary>

* Updated Gemini model.
* Upgraded packages.

</details>

<details>
<summary><strong>2.1.8 — 2025-11-28</strong></summary>

* Updated prompts.
* Added sensitive-word filtering.
* Added Overview and FIFU options.
* Updated title and keyword flows.

</details>

<details>
<summary><strong>2.1.7 — 2025-11-24</strong></summary>

* Upgraded the title-generation model.
* Updated prompts.

</details>

<details>
<summary><strong>2.1.6 — 2025-11-14</strong></summary>

* **[Permanent]** Removed Capture Process feature.
* Updated model handling for metadata, tags, and input article content.

</details>

<details>
<summary><strong>2.1.2 — 2025-11-11</strong></summary>

* Fixed Upload Google Docs feature.
* Updated URL replacement regex.

</details>

<details>
<summary><strong>2.1.1 — 2025-11-08</strong></summary>

* Added the ability to regenerate only metadata or tags.

</details>

<details>
<summary><strong>2.1.0 — 2025-10-27</strong></summary>

* Added Hide Main Window feature.
* Added Google Docs Online upload feature.

</details>

<details>
<summary><strong>2.0.8 — 2025-09-29</strong></summary>

* Added Move to Trash feature.

</details>

<details>
<summary><strong>2.0.7 — 2025-09-22</strong></summary>

* Added stop functionality for Generate Only.
* Added validation for each input file.

</details>

<details>
<summary><strong>2.0.6 — 2025-09-20</strong></summary>

* Changed API consumption flow.
* Improved Feedback UI.

</details>

<details>
<summary><strong>2.0.3 — 2025-08-28</strong></summary>

* Rewrote core functionality.
* Fixed several bugs.

</details>

<details>
<summary><strong>2.0.1 — 2025-08-19</strong></summary>

* Updated dynamic URL handling.

</details>

<details>
<summary><strong>2.0.0 — 2025-08-17</strong></summary>

* Major update to TON v2.
* Introduced new UI.
* Introduced new system.
* Added new features.
* Separated feature modules.

</details>

<details>
<summary><strong>1.1.8 — 2025-06-13</strong></summary>

* Updated Unsplash selector.

</details>

<details>
<summary><strong>1.1.7 — 2025-05-26</strong></summary>

* Updated Unsplash selector filter.

</details>

<details>
<summary><strong>1.1.6 — 2025-05-21</strong></summary>

* Updated random API key and image flow.

</details>

<details>
<summary><strong>1.0.6 — 2025-02-26</strong></summary>

* Reset state when stopping a process.

</details>

<details>
<summary><strong>1.0.5 — 2025-02-25</strong></summary>

* Fixed workflow logic.
* Improved process-stop handling.
* Updated compiler.

</details>

<details>
<summary><strong>1.0.2 — 2025-02-05</strong></summary>

* Added Generate & Auto Post mode.

</details>

<details>
<summary><strong>1.0.0 — 2025-01-10</strong></summary>

* Initial release.

</details>
