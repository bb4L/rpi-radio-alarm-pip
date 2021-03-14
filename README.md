# rpi-radio-alarm

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/rpi-radio-alarm)
[![PyPI](https://img.shields.io/pypi/v/rpi-radio-alarm)](https://pypi.org/project/rpi-radio-alarm/)
[![PyPI - Status](https://img.shields.io/pypi/status/rpi-radio-alarm)](https://pypi.org/project/rpi-radio-alarm/)
[![PyPI - License](https://img.shields.io/pypi/l/rpi-radio-alarm)](https://pypi.org/project/rpi-radio-alarm/)

![GitHub release (latest by date)](https://img.shields.io/github/v/release/bb4l/rpi-radio-alarm-pip)
![GitHub last commit](https://img.shields.io/github/last-commit/bb4l/rpi-radio-alarm-pip)


Package to simplify the communication to a instance of the [rpi-radio-alarm](https://github.com/bb4L/rpi-radio-alarm)

# Usage
`pip install rpi-radio-alarm`

## Objects
This package includes two classes.

### ApiHelper
This class can handle commands and arguments and send them to the [rpi-radio-alarm](https://github.com/bb4L/rpi-radio-alarm) and return the response

This is done in the `do_command(cmd, args)`, `cmd` has to be one of `constants.COMMANDS` and `args` is a dictionary with the appropiate values.

### RpiArgumentParser
The `RpiArgumentParser` parses string input to correct arguments for the ApiHelper.

### ResponseParser
This class defines for the `ApiHelper` how to parse the response from the [rpi-radio-alarm](https://github.com/bb4L/rpi-radio-alarm).

# Example Usages
[rpi-radio-alarm-discordbot-python](https://github.com/bb4L/rpi-radio-alarm-discordbot-python)

[rpi-radio-alarm-telegrambot](https://github.com/bb4L/rpi-radio-alarm-telegrambot/)

# License
[LGPLv3](LICENSE)
