Troubleshooting
===============

Jupyter Notebooks
-----------------

* Whie creating the Notebook make sure you chose R, Spark as the environment.
  The default will be Python, pay special attention to change this.
* Make sure the install.packages() ran correctly. You might need to restart the
  kernel and run the cells from the top after the pip install runs the first
  time.
* Many of the cells rely on variables that are set in earlier cells. Some of
  these are cleared in later cells. Start over at the top when troubleshooting.
* Many of the cells rely on service credentials from Bluemix that are set in
  earlier cells. Make sure to add your service credentials correctly.  
