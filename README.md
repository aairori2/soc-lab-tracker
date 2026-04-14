# soc-lab-tracker

Soil Organic Carbon (SOC) sequential fractionation tracker for a lab workflow.
https://aairori2.github.io/soc-lab-tracker/

## Overview

`soc-lab-tracker` is a web app for tracking the SOC sequential fractionation protocol across five fractions:

- Dry Free POM (FPOM)
- Wet Free POM (FPOM)
- Dissolved Organic Matter (DOM)
- Occluded Particulate Organic Matter (OPOM)
- Mineral-Associated Organic Matter (MAOM)

It helps manage sample status, protocol progress, timestamps, notes, and exports for lab reporting and analysis.

## Features

- Track samples through the full SOC fractionation workflow.
- Monitor progress across protocol steps and fractions.
- Store and sync data with Supabase.
- Fallback to localStorage for offline access.
- Export data for analysis and reporting.
- View protocol references and sample details in the browser.

## Data Source

The app is connected to Supabase for backend storage and uses browser localStorage as a fallback when network access is unavailable.

## Deployment

This project is designed to run as a static site, such as GitHub Pages.

## Notes

- The app is intended for lab use and workflow tracking.
- Data is organized around sample IDs and per-step protocol completion.
- The UI includes dashboard, today, timeline, samples, export, and protocol views.
