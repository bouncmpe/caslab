# CASLAB Website

## Local Development Instructions

1. Clone this repository and change the project directory:
   ```sh
   git clone git@github.com:bouncmpe/caslab.git
   cd caslab
   ```

2. Create a new virtual environment by running the following command:

   ```sh
   python -m venv ~/venv/mkdocs
   ```

   This will create a new virtual environment named `mkdocs` in the `~/venv` directory.

3. Activate the virtual environment by sourcing the activation script:
     
    ```sh
    source ~/venv/mkdocs/bin/activate
    ```

4. Once the virtual environment is activated, use `pip` to install requirements:

   ```sh
   pip install -r requirements.txt
   ```

   This will install MkDocs and other dependencies into the virtual environment.

5. To verify that MkDocs was installed successfully, run the following command:

   ```sh
   mkdocs --version
   ```

   This should display the version number of MkDocs.

6. Next, start the development server by running the following command:

   ```sh
   mkdocs serve
   ```

   This will start the development server, and you can view your site by visiting http://localhost:8000 in your web browser.

7. Add/modify/delete the markdown files under the `content` directory or modify `mkdocs.yml` for the site settings. Your changes will be immediately updated on your browser. 