# funcaptcha under developement
feel free to commit

## install funcaptcha
```
pip install funcaptcha
```
## current example (get key)
```python
from funcaptcha import Funcaptcha

funcap = Funcaptcha(
    api_url  = 'twitch-api.arkoselabs.com',
    api_key  = 'E5554D43-23CC-1982-971D-6A2262A2CA24',
    site_url = 'https://www.twitch.tv'
)

key = funcap.getkey()

print(f"Key: {key}")
```
