# Marshall Standby Mode Disabler

A simple script to disable the standby mode of Marshall speakers.

## Installation

```
git clone https://github.com/TheBananaWolf/SpeakerAlwaysOn.git
cd SpeakerAlwaysOn
python3 -m venv speakerAlwaysOn
source speakerAlwaysOn/bin/activate
pip3 install playsound
pip3 install PyObjC
```

## Getting Started

Execute the script using the following command:

```
python3 main.py
```

## How does it work?
This script plays an empty sound every 30 min, preventing your speaker from entering standby mode.

