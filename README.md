# auto-kudos
Python script that uses the pyAutoGUI library to scroll through a Strava activity feed and click thumbs-up icons to automatically give kudos to every activity in the feed.

## Installation

Follow these steps to set up and run **auto-kudos** using the Anaconda Prompt. Assumes you have installed Anaconda.

1. **Open Anaconda Prompt**
2. **Navigate to the Project Directory**

   Replace `<path-to-auto-kudos>` with the location where you have cloned or downloaded the `auto-kudos` repository:

   ```sh
   cd <path-to-auto-kudos>
   ```

3. **Create and Activate Conda Virtual Environment**

   ```sh
   conda env create -f environment.yml
   conda activate auto-kudos
   ```

4. **Run the Script**

   Use Jupyter notebook to run kudos.ipynb from the virtual environment. Two options:
   - Install notebook in the environment `conda install anaconda::notebook`, then run instance from environment `jupyter notebook`. Use browser GUI to open kudos.ipynb
   - Use code editor to run script from environment.
