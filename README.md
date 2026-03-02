# Netflix Genre Specialization Analysis

## Objective
The objective of this project is to analyze global movie and television production patterns to identify structural genre strengths across countries. Rather than relying solely on total content volume, the analysis aims to measure relative specialization and uncover competitive positioning within specific genres.

## Methodology
- **Data Cleaning & Preparation:**
Processed title-level data and standardized country and genre classifications.

- **Genre Aggregation**
Computed total content counts by country and genre for both Movies and TV Shows.

- **Relative Specialization Index (RSI):**
Developed a specialization metric to measure how strongly a country over-indexes in a genre relative to its global share. RSI comparesa acountry's share of a genre to its overall content share globally.

- **Comparative Analysis:**
Conducted side-by-side evaluation of Movies and TV to identify structural differences in diversification and specialization patterns.

## Executive Summary
This project analyzes global movie and television production patterns using exploratory data analysis and a custom Relative Specialization Index (RSI).

Initial analysis examined total production volumes by country and genre. While countries such as the United States and India dominate in scale, volume alone did not explain competitive positioning. To address this, an RSI metric was developed to measure genre specialization relative to global share.

Findings show that movies exhibit diversified production across major markets, with limited extreme specialization. In contrast, television content demonstrates stronger regional concentration and language-based dominance. Japan leads in Anime, South Korea in Korean TV, Mexico in Spanish-language TV, and the UK in British and documentary formats. The United States maintains scalable multi-genre strength, particularly in reality, sci-fi, and talk shows.

The analysis highlights a structural distinction: film production reflects global diversification, while television production reinforces cultural and domestic specialization.

## Key Insights
- **Volume ≠ Specialization:**
Large producers such as the United States and India dominate in total output but do not consistently exhibit extreme genre concentration.

- **RSI Reveals Structural Strength:**
The Relative Specialization Index (RSI) identified hidden competitive positioning beyond raw counts, highlighting true genre over-indexing.

- **Movies Show Diversification:**
Film production across major markets is broadly distributed across genres, with limited structural clustering.

- **Television Shows Stronger Cultural Anchoring:**
TV content demonstrates higher specialization intensity, particularly in language-based genres (e.g., Anime – Japan, Korean TV – South Korea, Spanish-language TV – Mexico, British TV – UK).

- **Mid-Sized Markets Display Clear Genre Identity:**
Countries such as Japan, South Korea, Mexico, and the UK show sharper niche dominance compared to high-volume producers.

- **Structural Industry Distinction:**
Film production reflects globalized diversification, while television production reinforces domestic and cultural specialization.

## Dataset
This analysis uses the Netflix Titles dataset, containing metadata on movies and television shows including country, genre classifications, and content type.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook