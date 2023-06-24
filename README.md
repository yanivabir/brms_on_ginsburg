# brms_on_ginsburg
Function to send a brms model to be fit on Ginsburg.

WIP - use with caution.
Use jobid <- launch_model(...) to send model to Ginsburg. Look at arguments to see what you need - this is similar to brms arguments. The only difference is that everything that is not a number needs to be passed as a string.

Use fetch_results(jobid, ...) to download fitted model to your local computer, after the job has finished.

Use check_status(jobid,...) to check the status of a running job.
