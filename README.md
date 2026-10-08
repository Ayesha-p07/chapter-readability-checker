# Chapter Readability Checker

A free browser-based tool where an author can paste a chapter and see:
- Flesch Reading Ease readability score
- Word count
- Sentence count
- Five hardest sentences

## AI tools used
ChatGPT was used to help plan the interface, generate the initial HTML/CSS/JavaScript structure, and debug the logic. The final tool should be tested manually with real writing samples.

## Important limitation
The tool can sometimes classify a long but understandable sentence as difficult because its scoring combines sentence length and word complexity. A future version could combine more readability metrics and vocabulary analysis.

## Deploy on GitHub Pages
1. Create a GitHub repository, for example `chapter-readability-checker`.
2. Upload `index.html`.
3. Open Settings → Pages.
4. Under Build and deployment, choose "Deploy from a branch".
5. Select the `main` branch and `/ (root)`.
6. Save. GitHub will generate a public live link.
