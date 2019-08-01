### tomorrow
---
https://github.com/madisonmay/Tomorrow

```py
import time
import requests

def download(url):
  return request.get(url)
  
if __name__ == "__main__":
  start = time.time()
  responses = [download(url) for url in urls]
  html = time.time()
  end = time.time()
  print "Time: %f seconds" % (end - start)


import time
import requests

from tomorrow import threads
@threads(1, timeout=0.1)
def raises_timeout_error():
  time.sleep(1)
if__name__ == "__main__":
  print raises_time_error()
  
import time
import requests

from tomorrow import threads

@threads(5)
def download(url):
  return requests.get(url)
  
if __name__ == "__main__":
  start = time.time()
  responses = [download(url) for url in urls]
  html = [response.text for response in responses]
  end = time.time()
  print "Time: %f seconds" % (end - start)

import time
from tommorror import threads
@threads(1, timeout=0.1)
def raises_timeout_error():
  time.sleep(1)

if __name__ == "__main__":
  print raises_timeout_error()
```

```sh
pip install tomorrow
git clone git@github.com:madisonmay/Tomorrow.git
sudo python setup.py install
nosetests -v
```

```
urls = [
  'http://google.com',
  'http://facebook.com',
  'http://youtube.com',
  'http://baidu.com',
  'http://yahoo.com'
]
```


