# CMSC 408 - Spring 2025 - Homework 8

# World Bank Indicator Analysis

## Overview

This assignment focuses on exploring the World Bank country dataset by writing and running a bunch of SQL queries.
The goal is to strengthen our skills in relational querying, aggregation, filtering, and data transformation, while also practicing documentation using Quarto and Python helper functions.
We investigate basic statistics (like number of countries and regions), build more complex reports (like pivot tables and percentage breakdowns), and handle special tasks like updating missing values.

## Files and folders

| File | Description |
|------|-------------|
| report.qmd | The main Quarto document to be completed and rendered to HTML |
| report.html | The final rendered HTML report |
| helpers.py | Python helper functions for loading the database and querying it |
| .env | Stores your database credentials (user, password, host, db name) |
| pyproject.toml | Poetry configuration file for dependency management |
| README.md | This file — a guide to the project setup and execution |

## Requirements

Make sure you have the following tools installed:

- Python 3.11+
- Poetry (Python dependency manager)
- Quarto CLI
- MySQL database access (via phpMyAdmin or MySQL CLI)
- VS Code with SQLTools extension

## How to Run the Project

- poetry install
- poetry shell
- quarto render reports/report.qmd --to html