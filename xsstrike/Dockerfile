FROM python:3.9.0

WORKDIR /xsstrike

RUN wget https://github.com/s0md3v/XSStrike/archive/3.1.5.tar.gz && \
	tar -xzvf 3.1.5.tar.gz && \
	cd XSStrike-3.1.5 && pip install -r requirements.txt

WORKDIR /xsstrike/XSStrike-3.1.5

CMD [python3, xsstrike.py, -h]


