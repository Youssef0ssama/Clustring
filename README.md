# Customer Segmentation & Association Rule Generator

## Overview

This Python program provides a robust solution for customer segmentation and association rule generation. It intelligently divides customers into (n) clusters based on their total spending and age, offering valuable insights into customer behavior. Additionally, users can extract meaningful association rules from transactional data by setting minimum support and confidence thresholds.

## Features

- **Customer Segmentation:** Efficiently groups customers based on their total spending and age.
- **Detailed Table:** Displays a comprehensive table with customer details, including name, age, total spending, and assigned cluster.
- **Association Rule Generation:** Enables users to extract association rules from transactional data.
- **Customizable Parameters:** Users can set minimum support and confidence thresholds for fine-tuning the association rule extraction process.

## Getting Started

1. **Installation:**
   ```bash
   pip install customer-segmentation-association
   ```

2. **Usage:**
   - Import the library and necessary functions in your Python script.
   - Call the segmentation and association rule functions with the required parameters.

```python
from customer_segmentation_association import segment_customers, generate_association_rules

# Customer Segmentation
segmented_customers = segment_customers(data, n_clusters)

# Association Rule Generation
association_rules = generate_association_rules(transactional_data, min_support, min_confidence)
```

3. **Example:**
   ```python
   # Example Usage
   from customer_segmentation_association import segment_customers, generate_association_rules

   # Customer Segmentation
   segmented_customers = segment_customers(customer_data, n_clusters=3)

   # Association Rule Generation
   association_rules = generate_association_rules(transactional_data, min_support=0.2, min_confidence=0.5)
   ```

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute, report issues, or suggest improvements!
