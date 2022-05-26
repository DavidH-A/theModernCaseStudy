# theModernCaseStudy
This is our TSE website code

In order to start the system, run the run.py file (preferably in Visual Studio Code).
If everything works you should see something similar to this:
 * Serving Flask app 'modernCaseStudy' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Running on http://127.0.0.1:5000 (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 118-741-590

 CLICK THE http://127.0.0.1:5000 LINK TO VIEW THE WEBSITE

===TROUBLESHOOTING===

OUR SYSTEM UTILISES LANGUAGES:
#Python 3 (Python Flask)
#HTML
#CSS
#Bootstrap 5 (& it's Javascript)

In order to run our system you will need to install the required python modules.

We have utilised 'pipenv' which is a combination of Python pip and venv. It handles the creating of the virtual enviroment.

THE SYSTEM WILL ATTEMPT TO INITIALLY AUTO-INSTALL DEPENDENCIES SUCH AS PipEnv and Python Flask
Should this fail:

In order to MANUALLY install dependencies such as pipenv and modules
In the python console input:
1.) {open console/terminal, ensure you are in the correct directory (.../ModernCaseStudy)}
2.) pip install --user pipenv
3.) pip install -r requirements.txt
4.) {run/execute 'run.py' (run.py as startup item)}
5.) {In webbrowser (preferably Chrome or FireFox) navigate to LocalHost http://127.0.0.1:5000}
