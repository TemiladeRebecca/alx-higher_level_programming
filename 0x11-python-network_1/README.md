# 0x11-python-network_1

## Task description:

* [0-hbtn_status.py](./0-hbtn_status.py): Python script that fetches
  `https://alx-intranet.hbtn.io/status`.
  * Uses `urllib` package.

* [1-hbtn_header.py](./1-hbtn_header.py): Python script that displays the
  `X-Request-Id` response header variable of a request to a given URL.
  * Usage: `./1-hbtn_header.py <URL>`
	* Uses `urllib` package.

* [2-post_email.py](./2-post_email.py): Python script that sends a `POST`
  request to a given URL with a given email, and displays the response body.
  * Usage: `./2-post_email.py <URL> <email>`.
	* Uses `urllib` package.

* [3-error_code.py](./3-error_code.py): Python script sends a request to
  a given URL and displays the response body.
  * Handles HTTP errors.
	* Uses `urllib` package.

* [4-hbtn_status.py](./4-hbtn_status.py): Python script that fetches
  `https://alx-intranet.hbtn.io/status`.
  * Uses `requests` package.


* [5-hbtn_header.py](./5-hbtn_header.py): Python script that displays the
  `X-Request-Id` response header variable of a request to a given URL.
  * Usage: `./5-hbtn_header.py <URL>`
	* Uses `requests` package.

* [6-post_email.py](./6-post_email.py): Python script that sends a `POST`
  request to a given URL with a given email, and displays the response body.
  * Usage: `./6-post_email.py <URL> <email>`.
	* Uses `requests` package.


* [7-error_code.py](./7-error_code.py): Python script sends a request to
  a given URL and displays the response body.
  * Handles HTTP errors.
	* Uses `requests` package.


* [8-json_api.py](./8-json_api.py): Python script that sends a `POST` request
  to `http://0.0.0.0:5000/search_user` with a letter passed as parameter.
  * Usage: `./8-json_api.py <letter>`
	* The letter is sent as the value of the variable `q`.
	* If no letter is given, sets `q=""`.
	* If the response body is properly formatted and non-empty, displays it as
  `[<id>] <name>`.
  * Uses `requests` package.

* [10-my_github.py](./10-my_github.py): Python script that takes GitHub
  credentials (username and password) and uses the Github API to display the
  corresponding ID.
  * Usage: `./10-my_github.py <username> <password>`
	* Uses `requests` package.

* [100-github_commits.py](./100-github_commits.py): Python script that lists
  the 10 most recent comments of a given GitHub repository using the GitHub API.
  * Usage: `./100-github_commits.py <repository name> <owner name>`
	* Uses `requests` package.
