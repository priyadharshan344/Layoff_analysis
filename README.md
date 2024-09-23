# Layoff_analysis

## Overview
The Layoff analysis of data empovers the quit understanding of layoff processes from many multinational companies and their corresponding laocations. This analysis provide clear sight of Technology market and it amount of requirement in a specific period.The following README provides a detailed account of the project's objectives, business problems, solutions, findings, and conclusions.

## Objectives
- Percentage of big layoffs
- Companies with highes laidoff
- Total and maximum laidoffs by locations
- Year over year laid off calculations

## Schema

```sql
CREATE TABLE `layoffs_staging` (
  `company` text,
  `location` text,
  `industry` text,
  `total_laid_off` int DEFAULT NULL,
  `percentage_laid_off` text,
  `date` text,
  `stage` text,
  `country` text,
  `funds_raised_millions` int DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;

