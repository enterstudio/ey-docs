# Create an environment

<b>Note:</b> In order to follow this procedure you must have at least one
application setup within your Engine Yard account.

## Create an Environment

  1. Login to your Engine Yard account.
  2. Click Dashboard.
  3. Navigate to an application by clicking on the application name.
  4. Click Create New Environment.
  5. Enter the information necessary for your environment. (See [[Environment options|environment-create#options]] below)
  6. Click Create Environment.

<h2 id="options"> Environment options</h2>

  * ### Environment Name
    Use underscores to separate words instead of spaces.  Common environment names are: myapp_production, myapp_staging, myapp_testing, myapp_qa, myapp_ci, etc.
  
  * ### Framework Environment
    Select an option to set the RAILS_ENV, MERB_ENV or RACK_ENV for applications in this environment.
  
  * ### Application Server Stack
    Select an application server to serve your Rails or Ruby application in this environment.  

    If you need to run more than one application on an environment, choose Passenger. 

	If you will be running only one application on an environment (this is more common practice), then choose Unicorn. Engine Yard has found Unicorn to be reliable, easier to monitor, and to have less downtime during deployment.
    
  * ### Runtime
    Select a runtime to run your applications in this environment.
    
  * ### Domain Name
    Set your domain name for this environment. This is the domain you intend to use for this application. If you are only adding one application to this environment, leave the Domain field blank (not set).
    
  * ### Region
    Select an AWS region for your environment. The default option is usually fine.
    
  * ### SSH Keys
    Select the ssh keys you want to have installed on instances in this environment.
    
  * ### Backups
    Select the frequency and amount of backups and snapshots you want to keep for this environment.
