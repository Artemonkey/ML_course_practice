# Machine Learning Course Practice

## How to run

1. Clone the repository:

    ```bash
    git clone https://github.com/Artemonkey/ML_course_practice.git
    ```
2. Navigate to the created directory:
   ```bash
   cd ML_course_practice
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run one of the Jupyter notebook:
   ```bash
   jupyter notebook 2. Clusterization models/japanese-heiroglyphs.ipynb
   ```
    or Open the notebook in your favorite IDE (VSCode, PyCharm, etc.) and run it there.
    ```bash
    # For VSCode, open the notebook file and click "Run All" in the top right corner of the notebook editor.
    code . // Mention the dot in the end
    ```

5. (Not mandatory) Set up Kaggle API credentials:
   - Create a Kaggle account if you don't have one.
   - Go to "Account" settings and create a new API token. Save token string in a safe place.
   Create a `.env` file in the root of the project and add the following line:
   ```
   KAGGLE_API_TOKEN=your_kaggle_api_token
   ```
   - Open the `kaggle.json` file and copy the values to your `.env` file:
     ```
     KAGGLE_API_TOKEN=your_kaggle_api_token
     ```
Course educator – Ph.D. in Technology, Associate Professor of the Department of Radio Electronics and Communications Dolganov, Anton Yu
