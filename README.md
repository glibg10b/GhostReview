# GhostReview

A framework for reviewing Stable Diffusion checkpoints in Python.

Before running the code, please verify that the 'Skip' column in the CSVs in PromptsForReviews/ do not contain "TRUE", otherwise the respective generations will be skipped.

The directory is under SDwebui. The script uses the API to generate images, but if the directory is under webui, it enters the image directory directly.
