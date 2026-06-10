# GitHub Upload Checklist

## Suggested Commit Message

`Prepare student performance analysis portfolio repo`

## Before Pushing

- Confirm the notebook opens as [Student_Performance_Analysis_Notebook.ipynb](Student_Performance_Analysis_Notebook.ipynb).
- Confirm the static preview opens as [Student_Performance_Analysis_Notebook.html](Student_Performance_Analysis_Notebook.html).
- Confirm the report is named [Student_Performance_Analysis_Report.pdf](Student_Performance_Analysis_Report.pdf).
- Confirm the preview image exists as [student_performance_preview.png](student_performance_preview.png).
- Confirm the license file exists as [LICENSE](LICENSE).
- Check that [README.md](README.md) reflects the renamed files.
- Verify [requirements.txt](requirements.txt) includes the packages needed to run the notebook.

## Recommended Push Order

1. `git status`
2. `git add README.md requirements.txt LICENSE student_performance_preview.png Student_Performance_Analysis_Notebook.ipynb Student_Performance_Analysis_Notebook.html Student_Performance_Analysis_Report.pdf GITHUB_UPLOAD.md`
3. `git commit -m "Prepare student performance analysis portfolio repo"`
4. `git push`

## Optional Extras

- Add a short project summary image or banner if you want the repo to look more polished on GitHub.
- If you later want a live demo, wrap the notebook into a Streamlit app and deploy that separately.
