# Working with Requests

The `requests` module in Python is a library used to send HTTP requests to websites and APIs.

We can retrieve data, submit data, download files, and interact with web services over the internet.

## Common Uses

* Send GET requests to retrieve data
* Send POST requests to submit data
* Download webpages and files
* Interact with REST APIs
* Automate web-related tasks

## Common HTTP Methods

### GET

Used to retrieve data from a server.

### POST

Used to send data to a server.

### PUT

Used to update existing data.

### DELETE

Used to remove data from a server.

## Example

```python
import requests

response = requests.get("https://example.com")

print(response.status_code)
print(response.text)
```

## Common Response Attributes

```python
response.status_code
response.text
response.json()
response.headers
```