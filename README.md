# Spot_Awareness

**Create Venv after cloning and run the following pip installs:**
  **1.** python3 -m pip install virtualenv
  **2.** python3 -m virtualenv --python=/usr/bin/python3 my_spot_env
  **3.** .\my_spot_env\Scripts\activate.bat
  **4.** python3 -m pip install --upgrade bosdyn-client bosdyn-mission bosdyn-choreography-client bosdyn-orbit
  **5.** python3 -m pip install bosdyn-client==5.0.0 bosdyn-mission==5.0.0 bosdyn-choreography-client==5.0.0 bosdyn-orbit==5.0.0

Ensure that the versions align with the ones below using: **python3 -m pip list --format=columns | findstr bosdyn**

  bosdyn-api                 5.0.0
  bosdyn-choreography-client 5.0.0
  bosdyn-client              5.0.0
  bosdyn-core                5.0.0
  bosdyn-mission             5.0.0
  bosdyn-orbit               5.0.0
