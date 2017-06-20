# Frontend for SPA «ПомойАвто»

It is a frontend for single page application. Reach JavaScript is present.

#### How it work:
* User enters email and password
* AJAX request is sent to the server with API, which is located on a separate subdomain [api.33_spa.devman.org](api.33_spa.devman.org).
* The server registers the user and gives cookies
* Frontend redirects to a page with a list of car users
* Frontend requests data from the server

# Deploy on localhost

Example of frontend launch on Linux, Python 3.5:

```bash
cd static/
python3 -m http.server 9000
```
Open page [http://localhost:9000/](http://localhost:9000/) in browser.

# Deploy on production server

[TODO. Deploy scripts will written later]

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
