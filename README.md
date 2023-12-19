# amtFMC_examples

Examples of amtFMC, amtery python library for FMC5030.

amtFMC is a Python library provided to remotely control FMC5030. The program is executed in an external host computer. With this method, python programs can control the tuner and AD9364 simultaneously.

To Startup, run the lines below. For more details, please refer to the examples or visit the [homepage](https://www.amtery.com/en).

```python
import amtFMC as fmc

# Reset and initialize FMC5030 through SSH.
fmc.amtFmcRfReset(ip, port, username, password)
```

##### Dependencies

- [LibIIO <= 0.25](https://github.com/analogdevicesinc/libiio/releases/tag/v0.25)

- [pyadi-iio <= 0.0.16](https://pypi.org/project/pyadi-iio/)

- [paramiko](https://pypi.org/project/paramiko/)

##### Installing from pip

```powershell
pip install amtFMC
```

##### Installing from source

Download the file on the homepage.

```powershell
# unzip the file to a specific path
7z x "amtFMC.zip" -o"C:\Program Files\"
cd C:\Program Files\amtFMC
pip install amtFMC-0.0.1-py3-none-any.whl 
```
