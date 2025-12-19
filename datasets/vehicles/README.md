# Vehicle Identity Dataset

This dataset contains structured identity information for a wide range of modern vehicles, including traditional internal combustion engine (ICE) vehicles, hybrids, and electric vehicles (EVs).

## Content

The dataset is provided in CSV format and includes high-level classification for popular vehicle models as of 2024-2025.

### Column Meanings

- `brand`: The manufacturer of the vehicle (e.g., toyota, tesla).
- `model`: The specific line of vehicle (e.g., corolla, model 3).
- `variant1`: Primary body style or classification (e.g., sedan, suv, truck).
- `variant2`: Powertrain type (e.g., gas, hybrid, electric).
- `variant3`: Trim level or specific sub-model (e.g., xle, performance, lightning).

## Data Processing

- **Normalization**: All text is converted to lowercase to ensure consistency.
- **Deduplication**: Exact duplicates of brand-model-variant combinations have been removed.
- **Tokenization**: Spaces are kept for readability but can be easily tokenized for NLP tasks.

## Example Rows

| brand | model | variant1 | variant2 | variant3 |
|-------|-------|----------|----------|----------|
| toyota | corolla | sedan | hybrid | le |
| ford | f-150 | truck | electric | lightning |
| tesla | model s | sedan | electric | plaid |

## Use Cases

- **Machine Learning**: Training classifiers for vehicle type or brand recognition.
- **Search & Filter**: Powering autocomplete or filter systems in automotive applications.
- **Data Analysis**: Market share analysis of EV vs. ICE body styles across luxury and economy brands.

## License

This dataset is released under **CC0 1.0 Universal**. It is part of the [Open Data Commons](file:///c:/Users/noname/Desktop/PERSONAL/OPENSOURCE/open-data-commons/README.md) project.
