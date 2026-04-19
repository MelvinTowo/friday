*** FRIDAY PROJECT ***
----------------------

Literally Iron mans assistant but not as advanced *yet*


** Project structure ** 
------------------------

```
friday/
├── main.py                  # Entry point
├── core/
│   ├── wake_word.py         # Wake word detection
│   ├── listener.py          # Whisper STT
│   ├── brain.py             # LLM + tool routing
│   ├── speaker.py           # TTS output
│   └── orchestrator.py      # Ties it all together
├── tools/
│   ├── app_control.py       # Open/close apps
│   ├── web_search.py        # Search the web
│   ├── email_reader.py      # Read emails
│   ├── calendar.py          # Calendar ops
│   └── notifications.py     # Read notifications
├── system/
│   ├── base.py              # Abstract OS interface
│   ├── macos.py             # Mac implementations
│   └── windows.py           # Windows implementations
├── ui/
│   └── ring.py              # Floating ring window
├── config/
│   └── settings.yaml        # Model paths, preferences
└── requirements.txt
```


