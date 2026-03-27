# Print Routing Rules

External catalog of printer routing rules for the Ultraprint Extension.

## Structure

- `index.json` - Catalog manifest with pack metadata
- `packs/` - Individual rule pack JSON files

## Usage

The Ultraprint Extension fetches these rules at runtime with local caching.

## Adding New Packs

1. Create new JSON file in `packs/`
2. Add entry to `index.json`
3. Increment catalog version
4. Commit and push
