# Cron

The cron job made in Python. Based originally on Akatsuki's cron job and adjusted for the needs of RealistikOsu!

## Available cron jobs
- Recalculate ranks (all modes and vanilla, relax, autopilot)
- Update total score
- Remove expired donor badges
- Add donor badges
- Calculate user playcount
- Recalculate user PP values (autopilot only for now)
- Restrict frozen players who's time to prove has passed.

## How to set up
- Install the required modules `pip3 install -r requirements.txt`
- Rename config.sample.ini to config.ini `mv config.sample.ini config.ini`
- Edit the config to your need.
- Run cron `python3 cron.py`
