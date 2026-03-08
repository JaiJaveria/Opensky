# ✈️ Opensky

A collection of tools built around **real-time aircraft tracking using ADS-B data**, focused on monitoring fleet activity of major Middle Eastern airlines (ME3).

This project was built while experimenting with the **OpenSky Network API** and related ADS-B data sources. It aggregates multiple components that ingest, process, and analyze aircraft state vectors.

---

## Repository Structure

- Opensky 
  - Opensky-backend   : Data ingestion and backend processing
  - Opensky-cron      : Scheduled polling jobs
  - skytrack          : Tracking and visualization utilities

Each component is maintained as its own repository and included here as **git submodules**.

---

## Features

- Fetch real-time aircraft state vectors
- Filter aircraft by fleet / ICAO addresses
- Persist aircraft data for analysis

---

## Setup

Clone the repository with submodules:

```bash
git clone --recurse-submodules https://github.com/<yourusername>/opensky.git
