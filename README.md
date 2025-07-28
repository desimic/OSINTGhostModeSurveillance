# OSINTGhostModeSurveillance
OSINT Counter-Surveillance - Watching the Watchers

├── src/
│   ├── main.py
│   ├── config.py
│   ├── alerts/
│   │   ├── signal_cli.py
│   │   ├── matrix.py
│   │   └── ntfy.py
│   ├── monitors/
│   │   ├── pastebin.py
│   │   ├── searxng.py
│   │   ├── spiderfoot_client.py
│   │   ├── masscan_watcher.py
│   │   ├── cert_watch.py      # crt.sh lookups (public, free)
│   │   └── canary_listener.py # optional OpenCanary hits
│   ├── store/
│   │   └── db.py
│   └── utils/
│       └── rules.py
├── requirements.txt
├── .env.example
├── setup.sh
└── README.md
