# Running the code locally in the Jupyter Notebook Environment

To set up the environment and install the necessary dependencies for running the Jupyter notebooks locally, follow these steps:

1. **Create a virtual environment (optional but recommended)**:
   ```sh
   python -m venv venv
   ```

2. **Activate the virtual environment**:
   must be run as administrator
   ```sh
   .\venv\Scripts\activate
   ```

3. **Install the requirements**:
   ```sh
   pip install -r requirements.txt
   ```

4. **Run Jupyter Notebook**:
   ```sh
   jupyter notebook
   ```

5. **Inside the Jupyter Notebook run Local environment part, NOT the Google Colab environment part**

When downloading the data from the GitHub, keras_metadata.pb is sometimes corrupted in some models.
If that is the case, don't hesitate to contact me on a.martykan@gmail.com