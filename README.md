# ML_Flow : MLflow is an open-source platform that helps Data Scientists and Machine Learning Practitioners manage their Machine Learning Projects. It provides a set of tools and functionalities that make it easier to Track, Reproduce, and Deploy Machine Learning Models. 


To run these commands from the command line, follow the steps below:

1. Open the command prompt (CMD) or a bash terminal.

2. Create a directory named "mlflow" by running the command:
   ```
   mkdir mlflow
   ```

3. Change the current directory to "mlflow" using the command:
   ```
   cd mlflow
   ```

4. Open the directory in your preferred code editor using the command:
   ```
   code .
   ```
   This command assumes you have Visual Studio Code installed. If you prefer a different editor, replace "code" with the appropriate command.

5. In the bash terminal, create a new Conda environment named "env" with Python 3.8 by running the command:
   ```
   conda create -p env python=3.8 -y
   ```

6. Activate the environment using the command:
   ```
   source activate ./env
   ```
   This command assumes you are using a Unix-based system. If you are on Windows, use the `conda activate` command instead.

7. In the CMD terminal, create a new Conda environment named "env" with Python 3.8 by running the command:
   ```
   conda create -p env python=3.8 -y
   ```

8. Activate the environment using the command:
   ```
   conda activate <absolute_path_of_env>
   ```
   Replace `<absolute_path_of_env>` with the absolute path of the "env" directory.

9. Alternatively, you can use the following command as a shortcut to create and activate the environment in one line:
   ```
   conda create -p env python=3.8 -y && source activate ./env
   ```

10. Create a file named "requirements_mlflow.txt" using the command:
    ```
    touch requirements_mlflow.txt
    ```

11. Install the required packages listed in "requirements_mlflow.txt" by running the command:
    ```
    pip install -r requirements_mlflow.txt
    ```

12. Verify the installed packages by running the command:
    ```
    pip list
    ```

13. Create a Python file named "first_trail.py" using the command:
    ```
    touch first_trail.py
    ```

14. Open the "first_trail.py" file in your preferred code editor and write your Python code.

15. Run the "first_trail.py" file by executing the command:
    ```
    python first_trail.py
    ```

16. Finally, to start the MLflow UI, run the command:
    ```
    mlflow ui
    ```

Make sure you have MLflow installed in your environment before running the commands. These steps will help you set up the necessary environment, install required packages, and execute the Python code using MLflow.
