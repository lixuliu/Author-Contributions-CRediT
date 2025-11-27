# Author Contributions - CRediT Tool

A web-based tool for managing and exporting author contributions using the Contributor Roles Taxonomy (CRediT) system.

## Features

- **Editable Author Names**: Enter author names directly in the table headers
- **Checkbox Selection**: Easily mark contributions by checking boxes for each author and contribution type
- **Add Multiple Authors**: Dynamically add author columns as needed
- **Dual Export Formats**: Export data in both CSV and TXT formats
- **Two Export Views**:
  - By Contribution Type: Rows show contribution types, columns show authors
  - By Author: Rows show authors, columns show contribution types
- **British English Spelling**: All contribution types use British English spelling (e.g., Conceptualisation, Visualisation)

## Contribution Types

The tool includes all 14 CRediT contribution types:

1. Conceptualisation
2. Data curation
3. Formal analysis
4. Funding acquisition
5. Investigation
6. Methodology
7. Project administration
8. Resources
9. Software
10. Supervision
11. Validation
12. Visualisation
13. Writing – original draft
14. Writing – review and editing

## Usage

1. **Enter Author Names**: Click on the author name field in the table header and type the author's name
2. **Mark Contributions**: Check the boxes to indicate which author contributed to which type of work
3. **Add More Authors**: Click the "Add Author Column" button to add additional authors
4. **Export Data**: Click "Export Data" to download four files:
   - `author_contributions_by_type.csv` - CSV format (by contribution type)
   - `author_contributions_by_type.txt` - TXT format (by contribution type)
   - `author_contributions_by_author.csv` - CSV format (by author)
   - `author_contributions_by_author.txt` - TXT format (by author)

## Export Format Details

### CSV Format

- Uses comma (`,`) as delimiter
- Properly handles commas and quotes in data

### TXT Format

- Uses colon (`:`) between first and second column
- Uses semicolon (`;`) between all other columns
- Example: `Contribution Type:Author1;Author2;Author3`

## Clear All

Use the "Clear All" button to reset all author names and checkbox selections.

## Browser Compatibility

This tool works in all modern web browsers. Simply open `contributions.html` in your browser.

## Copyright

© Copyright 2024 Dr Lixu Liu. All Rights Reserved.

## License

This software is protected by copyright. See the [LICENSE](LICENSE) file for details.

**Usage Terms:**

- ✅ Personal, educational, or research use is permitted
- ❌ Commercial use requires explicit written permission
- ❌ Modification, distribution, or sublicensing requires explicit written permission

For commercial use or other permissions, please contact Dr Lixu Liu.
