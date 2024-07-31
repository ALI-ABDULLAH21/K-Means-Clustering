

# K-Means Clustering on Mall Customer Dataset

This project demonstrates the implementation of the K-means clustering algorithm on the `Mall_Customer.csv` dataset to segment customers based on their spending patterns and income. 

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Customer segmentation is an essential task in marketing to understand the target audience better and to tailor products and services accordingly. In this project, we use the K-means clustering algorithm to segment mall customers based on their annual income and spending score.

## Dataset

The dataset used is `Mall_Customer.csv`, which contains the following columns:

- `CustomerID`: Unique ID for each customer.
- `Gender`: Gender of the customer.
- `Age`: Age of the customer.
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars.
- `Spending Score (1-100)`: Spending score assigned by the mall based on customer behavior and spending nature.

## Installation

To get started with the project, you need to have Python installed along with some necessary libraries. Follow the steps below to set up the environment:

1. Clone the repository:

   ```sh
   git clone https://github.com/ALI-ABDULLAH21/kmeans-mall-customers.git
   cd kmeans-mall-customers
   ```

2. Create a virtual environment:

   ```sh
   python -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:

     ```sh
     .\venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```sh
     source venv/bin/activate
     ```

4. Install the required libraries:

   ```sh
   pip install -r requirements.txt
   ```

## Usage

Follow the steps below to run the K-means clustering analysis:

1. Ensure you have the `Mall_Customer.csv` file in the project directory.

2. Run the Jupyter Notebook to perform clustering:

   ```sh
   jupyter notebook
   ```

3. Open the `KMeans_Mall_Customers.ipynb` notebook and run all cells to see the results of the clustering.

Alternatively, you can run the Python script if you prefer not to use Jupyter Notebook:

```sh
python kmeans_mall_customers.py
```

## Results

The K-means clustering algorithm segments customers into clusters based on their annual income and spending score. The resulting clusters can be visualized to understand different customer segments. Typically, customers are divided into segments such as:

- High income, high spending
- High income, low spending
- Low income, high spending
- Low income, low spending

These segments help businesses tailor their marketing strategies effectively.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

