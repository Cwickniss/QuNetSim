QuNetSim is a quantum-enabled network simulator that adds common quantum networking tasks like teleportation, superdense coding, sharing EPR pairs, etc. With QuNetSim, one can design and test robust classical-quantum network protocols under various network conditions.

Open docs/index.hmtl in a browser for documentation (still under construction, but some points are there)

SETUP INSTRUCTIONS

- Ensure Python3 (>=3.6) is installed / Install Python >=3.6 
- Clone the project
- At the same level as the cloned directory, create a virtual environment with the following:

To create:

`python3 -m venv venv`

To start:

`source venv/bin/activate`
  [WINDOWS] 
    Find out where your python resides using 'where python' command in CMD
    Then follow this guide https://www.c-sharpcorner.com/article/steps-to-set-up-a-virtual-environment-for-python-development/

- In the cloned directory (i.e. cd QuNetSim) install the python libraries:
To install packages in requirements.txt:

`pip install -r requirements.txt`

To stop the virtual environment (when not using the code) run:

`deactivate`
