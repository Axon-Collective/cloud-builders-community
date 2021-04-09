ARG PY_VERSION=3.7
FROM python:${PY_VERSION}-alpine

RUN curl https://bootstrap.pypa.io/ez_setup.py -o - | python
RUN pip install wheel twine yolk3k

ENTRYPOINT ["/bin/sh"]
