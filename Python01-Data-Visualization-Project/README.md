
# Amazon Product Data Visualization Project

This project visualizes Amazon product sales data using various data visualization techniques. The dataset includes attributes like product name, category, actual price, discounted price, rating, and more.

## Libraries Used

- **Pandas**: For reading and manipulating the dataset.
- **Matplotlib**: For creating visualizations such as bar charts, histograms, scatter plots, and pie charts.

## Steps in the Code

1. **Loading the Dataset**
   - The dataset is loaded from a CSV file (`amazon.csv`) using `pandas.read_csv()`.
   - Attributes include product name, category, actual price, discounted price, and rating.

2. **Bar Graph of Top 10 Product Categories**
   - Visualizes the top 10 most frequent product categories.
   - Helps identify the most prevalent categories in the dataset.

3. **Histogram of Product Ratings**
   - Displays the distribution of ratings (0 to 5).
   - Shows the spread and frequency of ratings.

4. **Scatter Plot of Actual Price vs Discounted Price**
   - Illustrates the relationship between actual and discounted prices.
   - Highlights patterns like higher actual prices correlating with larger discounts.

5. **Pie Chart of Product Distribution by Category**
   - Visualizes the proportion of products in the top 20 categories.
   - Helps understand the relative shares of each category.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-product-visualization.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib
   ```
3. Run the script to generate the visualizations:
   ```bash
   python script_name.py
   ```

## Dataset

Ensure that the `amazon.csv` dataset is in the project directory. The dataset should include the following columns:
- `Product Name`
- `Category`
- `Actual Price`
- `Discounted Price`
- `Rating`
