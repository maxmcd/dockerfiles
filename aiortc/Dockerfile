FROM python:3

RUN apt-get update && apt-get install -y build-essential \
    yasm libmp3lame-dev libopus-dev libvpx-dev libx264-dev \
    libavdevice-dev libavfilter-dev libopus-dev libvpx-dev pkg-config

RUN git clone https://github.com/jlaine/aiortc.git
RUN pip install aiortc uvloop

