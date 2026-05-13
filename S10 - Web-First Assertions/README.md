docker run -d -p 4444:4444 -p 7900:7900 --shm-size="2g" selenium/standalone-chrome:latest
export SELENIUM_REMOTE_URL=http://localhost:4444
pytest --browser chromium