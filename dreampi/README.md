# Usage
This requires Python 3 to be operational on your Pi (or other Linux machine for DreamCast connection)

To prepare the environment - this only needs to be done once:

```
apt-get install python3-venv
python3 -m venv .
source bin/activate
pip install -r requirements.txt
```

Then, to execute:

```
./dreampi.py [OPTION]...

Options:
    --no-daemon             don't daemonize or detach from shell
    --debug                 enable DEBUG logging (lots of output)
    --disable-dial-tone     don't try to generate dialtone - make sure to enable blind dialing (doesn't work with all games)
    --enable-upnp           enable the automatic port forwarding code (requires upnp router)
```