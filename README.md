```
   apt install python3.8-venv
   python3 -m venv venv
     ls
     source venv/bin/activate
     pip install -r requirement.txt 
     python run.py
     gunicorn --bind 0.0.0.0:5000 run:app
     nohup gunicorn --bind 0.0.0.0:5000 run:app &
```
