# Fizz Buzz REST Server

This Flask application serves as a Fizz Buzz REST Server, allowing users to apply Fizz Buzz logic with customizable parameters.

## *Special Build Instructions*

No special build instructions are required. Simply follow the usage instructions below.

## *Third-Party Libraries*

**Flask**: Used for building the web application.

**Flask-WTF**: Used for handling forms and form validation.


## API Documentation


## *Fizz Buzz Endpoint:*

URL: /
Method: POST
Parameters:
int1: First integer value
int2: Second integer value
limit: Limit for Fizz Buzz logic
str1: First string value
str2: Second string value

### *Example Request:*


{
  "int1": 3,
  "int2": 5,
  "limit": 15,
  "str1": "Fizz",
  "str2": "Buzz"
}

### *Example Response:*


1, 2, Fizz, 4, Buzz, Fizz, 7, 8, Fizz, Buzz, 11, Fizz, 13, 14, FizzBuzz 


## *Statistics Endpoint:*

URL: /statistics
Method: GET

### *Example Response:*

{
  "hits": 42,
  "most_used_request": {
    "int1": 3,
    "int2": 5,
    "limit": 100,
    "str1": "Fizz",
    "str2": "Buzz"
  }
}

## Usage


## *Clone the repository:*

### Navigate to the project directory:

*cd FizzBuzz *

### Install dependencies:

`pip install -r requirements.txt`

## *Run the application*:

`python app.py`

Access the application in your browser at *http://127.0.0.1:8000/*

* run the test case /testcases/test_app.py *
