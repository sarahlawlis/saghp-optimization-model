# Single Airport Ground Holding Problem

### Background

Traffic Flow Management (TFM) is an area of research with the goal of managing traffic flow in an airspace in accordance to changing supply and demand. The motivation behind TFM is prioritizing safety and efficiency to meet these demands while responding to uncertainty. A Ground Holding Problem (GHP) is an optimization problem within TFM that uses airport capacity constraints to assign ground delays to flights in order to minimize the sum of the cost incurred from these delays. Our team set out to solve a Single Airport Ground Holding Problem (SAGHP) for the San Diego International Airport (SAN) since this is a high-volume airport with a single runway.

### Installation

To run the Single Airport Ground Holding Problem project, you need to have Jupyter Notebook installed along with several Python libraries. Below are the steps to set up the environment:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sarahlawlis/saghp-optimization-model.git
   cd saghp-optimization-model
   ```
2. **Create a virtual environment:**
   ```bash
   python -m venv <env_name>
   source env_name/bin/activate
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   * **Install Jupyter Notebook if you haven't already:**
   ```bash
   pip install jupyter
   ```
4. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
5. **Open the saghp_model notebook**

### Usage

1. **Load the Notebook:**
   - Open the `saghp_model.ipynb` file in Jupyter Notebook.

2. **Run the Cells:**
   - Execute the cells in order by selecting a cell and clicking the "Run" button or using `Shift + Enter`.
   - The notebook will guide you through the data loading, model setup, and optimization process.

3. **Input Data:**
   - The required input data is included in the repository in the `data/` directory. Ensure that the notebook correctly references these files. The data files are already provided, so you don't need to manually download or place them.

4. **Analyze Results:**
   - After running the optimization model, the notebook will display results of flights delayed.