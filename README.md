# flickr-metadata-eda
Exploratory data analysis and cleaning pipeline for a large, messy Flickr metadata dataset. The tasks were merging inconsistent XML/JSON sources into a unified dataset, then using statistical testing to discover behavioural patterns in how users tag, upload, and engage with content.

## Overview

Raw Flickr metadata is fragmented across multiple export formats and rarely consistent in structure. This project builds a reproducible wrangling pipeline to merge, clean, and validate ~33,000 records, then applies exploratory and statistical methods.

## What we did

- Merged and cleaned ~33,000 records from separate XML and JSON sources into one unified dataset
- Analysed temporal posting patterns to classify distinct user posting behaviours
- Segmented users into behavioural archetypes based on metadata completeness, tag usage, and upload frequency
- Identified content communities and metadata patterns, using statistical testing (i.e., chi-square) to confirm that missing data was systematic rather than random

## Tools

- Python; pandas, numpy, matplotlib, seaborn
- XML/JSON parsing
- Statistical testing (scipy)

## Repository contents

- `presentation slides/` — presentation on analysis findings and insights

> Note: Cannot upload the notebooks due to the file size.

## My contribution

This was a group assignment for the Data Wrangling unit at Monash University.
My role focused on Exploratory Data Analysis (EDA) by applying basic sanity check and focusing in bivariate analysis.

## Team

- Mutiara Hernowo
- Stefanus Felix Wigna Sunarto
- Mutia Salsabila
- Ferina Lestari Damamain
- Catharina

## Academic context

Group assignment, Data Wrangling unit, Monash University, 2026. Shared here with
team consent for portfolio purposes.
