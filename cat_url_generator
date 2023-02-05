import requests

# API endpoint
url = 'https://api.thecatapi.com/v1/images/search'

# Make request to the API
response = requests.get(url)

# Get the response data as a python object
data = response.json()
dic = data[0]
print(dic['url'])
