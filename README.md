# RFM Customer Segmentation

This project utilizes RFM (Recency, Frequency, Monetary) analysis to segment customers based on their purchasing behaviors, enabling targeted marketing strategies and improved customer relationship management.

<a href="https://www.github.com/elifpulukcu">
    <img src="https://miro.medium.com/max/1190/1*SMx8ZNSq5ZLZSPh2u_peSw.png" width="800" align="center"></a>

## Project Overview

RFM analysis is a marketing technique used to evaluate and segment customers based on their transaction history:

- **Recency (R):** How recently a customer made a purchase.
- **Frequency (F):** How often a customer makes a purchase.
- **Monetary (M):** How much money a customer has spent.

By scoring customers on these three factors, businesses can identify customer segments that are crucial for personalized marketing efforts.

## Dataset

The dataset used in this project is the [Online Retail II dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II) from the UCI Machine Learning Repository. It contains transactions occurring between 01/12/2009 and 09/12/2011 for a UK-based online retail store.

## Repository Contents

- `RFM.ipynb`: Jupyter Notebook containing the implementation of RFM analysis and customer segmentation.
- `data/`: Directory containing the dataset used for analysis.
- `images/`: Directory containing visualizations generated during the analysis.
- `README.md`: Project overview and instructions.

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/elifpulukcu/RFM-Customer-Segmentation.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd RFM-Customer-Segmentation
   ```

3. **Run the Jupyter Notebook:**

   ```bash
   jupyter notebook RFM.ipynb
   ```

## Analysis Steps

1. **Data Preprocessing:**

   - Load the dataset.
   - Handle missing values and duplicates.
   - Convert data types as necessary.

2. **RFM Metric Calculation:**

   - Calculate Recency, Frequency, and Monetary values for each customer.

3. **Customer Segmentation:**

   - Assign RFM scores to each customer.
   - Define customer segments based on RFM scores.

4. **Data Visualization:**

   - Generate visualizations to illustrate customer segments and insights.

## Results

The analysis segments customers into distinct groups, such as:

- **Champions:** Recent, frequent, and high-spending customers.
- **Loyal Customers:** Regular purchasers with moderate spending.
- **At Risk Customers:** Customers who haven't purchased recently.

These segments enable the development of targeted marketing strategies to enhance customer engagement and retention.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- The dataset is sourced from the UCI Machine Learning Repository: [Online Retail II dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II).
- Inspiration for this project was drawn from various RFM analysis implementations and customer segmentation studies.

## Author

Developed by [Elif Pulukçu](https://github.com/elifpulukcu).



