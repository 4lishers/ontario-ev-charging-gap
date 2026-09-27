# Ontario EV Charging Gap 

**Question:** Which Ontario communities have the most electric vehicles but the fewest public charging ports?

## Status
🚧 In progress

## Data sources
- Electric Vehicles in Ontario by Forward Sortation Area (Ontario Data Catalogue)
- Electric Charging Station Locator (Natural Resources Canada)
- 2021 Census population by Forward Sortation Area (Statistics Canada)

## Tools
Python (pandas), SQL (SQLite), Power BI

## Approach
1. Clean postal codes and convert them to FSAs (first 3 characters, e.g. L7L)
2. Join EV counts, charging ports, and population by FSA
3. Calculate EVs per public charging port to find underserved areas
4. Build a Power BI dashboard

## Findings
Coming soon.
