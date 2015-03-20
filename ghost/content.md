# Ghost

Ghost is a free and open source blogging platform written in JavaScript and distributed under the MIT License, designed to simplify the process of online publishing for individual bloggers as well as online publications.

> [wikipedia.org/wiki/Ghost_(blogging_platform)](http://en.wikipedia.org/wiki/Ghost_%28blogging_platform%29)

%%LOGO%%

# How to use this image

	docker run --name some-ghost -d ghost

This will start a Ghost instance listening on the default Ghost port of 2368.

If you'd like to be able to access the instance from the host without the container's IP, standard port mappings can be used:

	docker run --name some-ghost -p 8080:2368 -d ghost

Then, access it via `http://localhost:8080` or `http://host-ip:8080` in a browser.