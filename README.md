# Prerequisites
Jenkins should be installed and running on localhost.

You must have set up your username and password during the initial setup.

# Creating a New Job in Jenkins
Access Jenkins Dashboard
Open your browser and navigate to:
    http://localhost:8080
# Login
Use your Jenkins credentials (username and password) to log in.

# Create a New Item

Click on “New Item” on the left-hand side.

Enter a name for your job.

Select Freestyle project (great for beginners).

Click OK.

# Configure Your Job
You will now be in:
    Dashboard > Job Name > Configuration

General Section: Add a meaningful description of the job.

 # Build Section:

Scroll down to Build.

Click on Add build step → select Execute shell.

Enter your shell commands to be executed during the build.

# Save the Configuration

Click Save to finalize your job configuration.

You will be redirected to the job’s main page.



# ⚙️ Running Your Job
On the left sidebar, click on Build Now.

A build will be triggered.

You will see #1 under the Build History, which means your first build has run successfully.

Click on the build number (e.g., #1) to view detailed logs and results.

# ✅ Congratulations!
You have successfully created and run your first Jenkins job! 🎉