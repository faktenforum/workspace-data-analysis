# Data Analysis Workspace

Persistent workspace repository for Data Analysis agent with Python scripts and sample data.

## Structure

- `examples/` - Python scripts (matplotlib/seaborn chart types, pandas patterns), sample CSVs
- `.mcp-linux/plan.json` - Workspace plan (resets on main branch checkout)

## Usage

Agents clone this repo as a workspace and work on task branches. Main branch stays clean.
