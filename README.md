# Emailqueue docker developer #
**A developer environment for Emailqueue developers**

By Tin.cat (https://tin.cat)

This is a docker project for Emailqueue developers, based on (https://github.com/tin-cat/emailqueue-docker).

Once started up, the following services will be available:

* Emailqueue will be running on localhost:8081
* Emailqueue front end will be available on http://localhost:8081/frontend
* Emailqueue API will be available on http://localhost:8081/api
* Mailcatcher (https://mailcatcher.me) will be acting as a fake SMTP, whose frontend will be available on http://localhost:1080 to check the delivered emails.

You're able to run some useful commands via make, type `make` to see a list of them.