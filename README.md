# Telegram bot for habit tracking 

## Commands
`/add_pixel`

# Habit_tracker
Habit tracker for cycling using Pixela API (https://pixe.la/)
## Overview
This script allows to create a heatmap that helps you track your habits eg how long you've cycled for each day. 

## Functions

`add_pixel_today(quantity, graph_id)` - add a pixel to the current day.

Purpose: Adds a pixel to represent your progress for the current day.

Parameters:
- `quantity`: The amount of cycling activity (e.g., kilometers or minutes).
- `graph_id`: The ID of the Pixela graph where the data will be logged.
