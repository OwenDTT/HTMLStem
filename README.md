# HTMLStem
A HTML stem separator, made with python and html.
Use this free tool to seperate stems in your audio files.
Uses https://github.com/lucidrains/BS-RoFormer for seperation.
Required dependices:

Python 3.0+
  
ffmpeg 

```pip install flask```

```pip install "audio-separator[cpu]"```

If you have an NVIDIA gpu use this instead of cpu 
```pip install "audio-separator[gpu]"```

Then, once you have the depdencies installed run by using 
```python3 server.py```

Avalible at http://localhost:5150 or http://127.0.0.1:5150
