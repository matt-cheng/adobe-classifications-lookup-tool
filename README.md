# Classificaiton Lookup Tool

A lightweight browser-based tool for populating a column in one file using a lookup from another — no installs, no server, no data ever leaves your machine.

## What it does

Upload a **source file** (the reference data) and a **target file** (the file you want to update). Select which columns to match on and which column to populate, then download the result instantly.

Built for populating fields like "Friendly Campaign Name" by matching a Campaign ID across files, but the column dropdowns are fully flexible — it works for any similar lookup task.

## Supported formats

`.xlsx`, `.xls`, `.csv`, `.tsv`

## Usage

1. Upload your **source file** and select the key and value columns
2. Upload your **target file** and select the lookup key and the column to populate
3. Optionally toggle whether to include unmatched rows in the output
4. Click **Run lookup & download** — the updated file downloads automatically, named `[original filename]_updated.[ext]`

## Running locally

Just open `index.html` in a browser. No dependencies to install.

## GitHub Pages

Live at: `https://<your-username>.github.io/<repo-name>`
