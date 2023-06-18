# venv
Venv commands
To use Python virtual environments (virtualenv) in Linux, follow these steps:

1. Open a terminal window.

2. Install `virtualenv` package if you don't have it already. Run the following command:

   ```
   Copy code
   pip install virtualenv
   ```

3. Create a new virtual environment. Navigate to the desired directory and run the following command:

   ```
   Copy code
   virtualenv myenv
   ```

   Replace `myenv` with the desired name for your virtual environment.

4. Activate the virtual environment by running the activation script. Use the following command:

   ```
   bashCopy code
   source myenv/bin/activate
   ```

   Once activated, you should see the name of the virtual environment `(myenv)` at the beginning of the command prompt.

5. Install packages and work with your Python project as usual. Any packages you install will be isolated within the virtual environment.

6. When you're done working within the virtual environment, you can deactivate it. Simply run the following command:

   ```
   Copy code
   deactivate
   ```

   The virtual environment will be deactivated, and you will return to your system's default Python environment.

Using a virtual environment allows you to isolate dependencies for different projects, avoiding conflicts and ensuring project-specific package versions. You can create and activate multiple virtual environments as needed for different projects.
