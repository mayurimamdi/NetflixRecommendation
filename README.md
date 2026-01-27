Netflix Rating Classification Project

📌 Project Overview
This project explores the Netflix Movies and TV Shows dataset with the goal of predicting content ratings (e.g., TV-MA, PG-13, R, etc.) using metadata available in the dataset.
As someone new to working with entertainment metadata, this project was also a learning exercise in problem formulation, feature engineering, and understanding the limits of data-driven models.


📂 Dataset Description
The dataset contains information about Netflix titles with the following columns:
show_id – Unique identifier
type – Movie or TV Show
title – Name of the content
director – Director name (may be missing)
cast – Cast list
country – Country of production
date_added – Date added to Netflix
release_year – Year of release
rating – Content rating (target variable)
duration – Duration in minutes or number of seasons
listed_in – Genres
description – Short summary of the content


🎯 Problem Statement
The initial objective was to predict the Netflix rating of a title using available metadata.
This was framed as a multi-class classification problem, where the target variable (rating) is categorical.