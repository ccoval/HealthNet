201505-02-SWEN-261-TEAM-C-Team Stack OverFlowed
HealthNet Project (a health care website)

Team members: Christian Borges,
              Connor Coval,
              Zach Moran,
              Adam Rock


Target Environment:
    Python 3.4.3
    Django 1.9.1
    


Instructions:
    1. Unzip the Release2Beta.zip file and place the contents onto your Desktop (not necessary, but then a different path must be used in step 2).
    2. Using the 'cd' command in Command Prompt navigate into the first mysite folder containing the manage.py file
        which should be the following command path: ($ cd Desktop/HealthNetCode/mysite)
    3. In Command Prompt run the command 'python manage.py runserver'.
    4. Open a web browser(Not Mozilla FireFox as it is not compatible) and enter the url 'http://localhost:8000/HealthNet/'
    5. You may now either register as a new patient or use a premade account displayed below.
    6. New Doctors, Nurses, and Admins need to be validated before the account will work; this can be completed by the existing Health Admin(cuddy@email.com)


Known bugs and disclaimers:
    1. Images do not display the actual image when uploaded and viewed.
    2. Modifying an Appointment only works if the time/date you are changing
        it to does not overlap the original time as it counts itself as an appointment in the system.
    3. Not selecting a hospital when transferring a patient will return you 
        to the list of transferrable patients and not tell you why.
    4. Admin Registration Forms take 2 submit clicks to properly submit.
    5. Message Forms also take 2 submit clicks to properly submit.
    6. Results of Tests always are shown regardless of if Test.hasResults is True or not



Execution and Usage Instructions(logins & passwords)
    admin@email.com and cuddy@email.com users are pre-loaded, but other users listed below
    must be loaded using the "Import Record into HealthNet with a CSV" feature accessible
    via the HealthNet Home Page of the pre-loaded admin account (admin@email.com) or manually
    using the normal HealthNet registration process. The InitialSetup.csv file included in 
    HealthNet.zip, contains the information necessary for the HealthNet system to generate 
    the users below along with additional unlisted users, messages, etc.
    
    You may register a Patient account or access one of our pre-made user accounts such as:

                               Users:                             Hospital:
    a.Patient -        Username: zach@email.com          - Strong Memorial Hospital
                       Password: testpassword


    b.Nurse -          Username: chase@email.com         - Strong Memorial Hospital
                       Password: testpassword


    c.Doctor -         Username: house@email.com         - Strong Memorial Hospital
                       Password: testpassword


    d.System Admin -   Username: admin@email.com
                       Password: adminpassword


    d.Health Admin -   Username: cuddy@email.com         - Strong Memorial Hospital
                       Password: testpassword
    - Accounts/passwords are Case-Sensitive. Patient accounts may require validation
    from an administrator account before being usable.

Note - Accessing any urls that you know of for our site by accounts that are not authorized
should land you on an account not authorized page. Similar situation if you are not logged in.
