Simple HTTP server returning calendar entries for all [Wekan](https://github.com/wekan/wekan) cards with set due date. To be used with Lightning or similar calendar app (read-only).
Yes, it's not the best solution, but it does the job (at least for me).
Depends on: https://github.com/wekan/wekan-python-api-client

Running:
`python wekan_ical_server.py`
(don't forget to set your Wekan url and login/passwd)
then add new network calendar in your app with url: `http://LISTEN_HOST:LISTEN_PORT`
Done.
