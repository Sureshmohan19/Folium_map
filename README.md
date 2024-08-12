# Folium_map
# GDHI Visualization Project

This repository contains a Jupyter Notebook that visualizes data related to the Global Domestic Happiness Index (GDHI) in the UK. The notebook helps to visualise the data in Folium map using shapefiles obtained from the official site (ONS).

## Repository Contents

- **`GDHI_visualisation.ipynb`**: The main Jupyter Notebook that contains all the code for data visualization.
- **ukshapefile**: All shape files that are used in the notebook should be placed in the appropriate directory within the repository.
- **gdhi.xlsx**: GDHI data used in the notebook should be placed in the appropriate directory within the repository.

## Prerequisites

Before running the notebook, ensure you have the following installed on your system:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Git (for version control and cloning the repository)

## Setup Instructions

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone https://github.com/username/repository-name.git
```

Navigate to the cloned directory:

```bash
cd repository-name
```

### 2. Create and Activate a Virtual Environment

It's recommended to use a virtual environment to manage dependencies. Run the following commands to set up and activate a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

### 4. Run the Jupyter Notebook

Start the Jupyter Notebook server:

```bash
jupyter notebook
```

Open the `GDHI_visualisation.ipynb` file in your browser and run the cells to generate the visualizations.

## Usage

The notebook is designed to be run sequentially, with each cell containing specific steps for loading data, processing it, and visualizing the results. This is just a small version and allowed users to leverage the existing shapefile and GDHI data to analyse or visualise more. 

## Troubleshooting

- **File Paths**: Ensure that the data files are in the correct directory as specified in the notebook. Adjust the file paths in the notebook if necessary.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the Apache 2.0 License. See the `LICENSE` file for details.

## Acknowledgments

Thanks to the contributors and sources of the data used in this notebook.
