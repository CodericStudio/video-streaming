# video-streaming

### Requirements
- python 3
- virtualenv
- pip
- kafka
```
brew install kafka
```

### Setup & Running application

To run locally:

```
brew services start zookeeper

brew services start kafka

virtualenv env && source env/bin/activate

pip install -r requirements.txt

python producer.py

python consumer.py
```

Video streaming at `http://0.0.0.0:5000`
