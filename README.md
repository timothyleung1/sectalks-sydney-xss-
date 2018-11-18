# XSS Challenges for Sectalks Sydney 
Flask was used for running the web application.
Selenium was used to trigger the XSS payload in the backend. 
Deploy with gunicorn instead of uwsgi instead. Challenge 2 requires a long HTTP request. Please patch the maxrequest line in the package.
