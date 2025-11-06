<h1 align="center"> Forensic</h1>
<h3 align="center">Live Forensicator for MacOS</h3>


#  ABOUT

Live Forensicator is part of the Black Widow Toolbox, its aim is to assist Forensic Investigators and Incidence responders in carrying out a quick live forensic investigation.
<p>It achieves this by gathering different system information for further review for anomalous behaviour or unexpected data entry, it also looks out for unusual files or activities and points it out to the investigator.</p>
<p> **This is the MacOS version written in Bash. </p>
<p>It is paramount to note that this script has no inbuilt intelligence its left for the investigator to analyse the output and decide on a conclusion or decide on carrying out more deeper investigation.</p>


##  Usage

```python
# copy the files to the computer
git clone https://github.com/brianlinhung/Live-Forensicator.git

# move into the MacOS directory
cd MacOS

# Give permission
chmod 777 Forensicator.sh

# Execution
./Forensicator.sh

```

##  Examples

```python
# All Feature Execution
./Forensicator.sh

```

##  Notes
* Run the script on a root shell to get value.<br>

* Make sure your terminal has Full Disk Access Permission.<br>
  You can set this from system settings > privacy & security<br>

* You can find all extracted Artifacts in the script's working directory.
  Use the index.html page to easily navigate the findings from Menu.


## What Forensicator Grabs
```bash

   =================================
     USER ACTIVITY
   =================================
     1. USER DOWNLOADS

   =================================
     SYSTEM INFORMATION
   =================================
     1. SYSTEM INFORMATION.
     2. INSTALLED APPLICATIONS.
     3. USER ACCOUNTS
     4. ADMINISTRATIVE USERS
     5. INBUILT SECURITY TOOLS STATUS

   =================================
     NETWORK INFORMATION
   =================================
     1. NETWORK INFORMATION.
     2. NETWORK CONNECTIONS

   ========================================
     AUTO STARTS
   ========================================
    1. LAUNCH AGENTS.
    2. DAEMONS
    3. CRON JOBS
    
   ========================================
     SYSTEM LOGS
   ========================================
    1. LOGIN WINDOWS
    2. KERNEL LOGS
    3. AUDIT LOGS
    4. USER LOGIN LOGS
    5. USER ACTIVITY LOGS
    6. LOG DIFFERENCE (BETWEEN DATES)

    NOTE: STILL IN BETA .

   =================================
     HISTORIES
   =================================
    1.  INSTALL HISTORY
    2.  LOCATION SERVICE REQUESTS
    3.  COMMAND HISTORY
    4.  TCC (Transparency, Consent, and Control)


```

<h3 align="left">Support:</h3>
<p><a href="https://ko-fi.com/forensicator"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="ebuka" /></a></p><br><br>




