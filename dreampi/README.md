# Usage
This requires Python 3 to be operational on your Pi (or other Linux machine for DreamCast connection)

To prepare the environment - this only needs to be done once:

```apt-get install python3-venv
python3 -m venv .
source bin/activate
pip install -r requirements.txt```

Then, to execute:

```./dreampi.py --no-daemon```