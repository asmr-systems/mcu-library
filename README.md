# Microcontroller Library
A library of datasheets, headers, startup-code, etc. for microcontrollers used in ASMR labs.

The purpose of this repository is to vendor all third-party code and assets related to the microcontrollers we use.

## Getting Started
To add new microcontrollers or assets to this repository, use the [`asmr cli toolkit`](https://github.com/asmr-systems/toolkit).
``` shell
python3 -m venv venv            # create a virtual env.
. venv/bin/activate[.fish]      # activate env [in fish].
pip install -r requirements.txt # install asmr toolkit
```

Now we can fetch materials for supported a supported mcu.
``` shell
asmr mcu fetch <mcu> <asset>
```
