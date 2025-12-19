# Vehicle Identity Dataset

This dataset contains structured identity information for a wide range of modern vehicles, including traditional internal combustion engine (ICE) vehicles, hybrids, and electric vehicles (EVs).

## Content

The dataset is provided in CSV format and includes high-level classification for popular vehicle models as of 2024-2025.

### Column Meanings

- `brand`: The manufacturer of the vehicle (e.g., maruti).
- `model`: The specific line of vehicle (e.g., alto).
- `variant1`: Variant of the vehicle (e.g., k10).
- `variant2`: Variant of the vehicle (e.g., lxi).
- `variant3`: Variant of the vehicle (e.g., manual).

## Data Processing

- **Normalization**: All text is converted to lowercase to ensure consistency.
- **Deduplication**: Exact duplicates of brand-model-variant combinations have been removed.
- **Tokenization**: Spaces are kept for readability but can be easily tokenized for NLP tasks.

## Example Rows

| brand  | model | variant1 | variant2 | variant3 |
|--------|-------|----------|----------|----------|
| maruti | alto  | k10      | lxi      | manual   |


## Use Cases

- **Machine Learning**: Training classifiers for vehicle type or brand recognition.
- **Search & Filter**: Powering autocomplete or filter systems in automotive applications.
- **Data Analysis**: Market share analysis of EV vs. ICE body styles across luxury and economy brands.

## License

This dataset is released under **CC0 1.0 Universal**. It is part of the [Open Data Commons](open-data-commons/README.md) project.
