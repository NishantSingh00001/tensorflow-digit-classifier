# Security review — 20-point pen-test checklist (2026-11-19)

This repo is a single Jupyter notebook (`train_model.ipynb`) that trains an MNIST digit classifier
in Google Colab. There's no server, no API, no stored user data, no auth, and nothing that takes
input from anyone but the person running the notebook. All 20 checks are not applicable — there's
no application surface for any of them to apply to.

No fixes needed.
