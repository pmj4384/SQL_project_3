# # 🎵 Spotify Tracks Analysis

**SQL analysis of Spotify data with audio features, streams, and YouTube metrics.**

[![SQL](https://img.shields.io/badge/SQL-Window%20Functions%20CTEs-blue?style=for-the-badge&logo=postgresql)](https://postgresql.org)

## What it does
Analyzes thousands of Spotify tracks to find:
- Billion-stream hits
- Top 3 tracks per artist (using DENSE_RANK)
- Spotify vs YouTube performance
- Album energy ranges (CTE)
- Official video stats

## Key SQL skills
- Window functions: `DENSE_RANK() OVER(PARTITION BY artist...)`
- CTEs for clean multi-step logic
- Data cleaning + aggregations
- Subqueries for dynamic filters

## Run it
1. CREATE TABLE spotify
2. LOAD CSV data  
3. Run queries
