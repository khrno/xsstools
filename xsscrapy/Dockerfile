FROM python:2.7.18

WORKDIR /xsscrapy

RUN wget https://github.com/DanMcInerney/xsscrapy/archive/master.zip && \
	unzip master.zip && rm master.zip && \
	cd xsscrapy-master && pip install -r requirements.txt

WORKDIR /xsscrapy/xsscrapy-master

CMD [python, xsscrapy.py, -h]
